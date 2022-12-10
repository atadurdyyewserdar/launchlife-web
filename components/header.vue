<template>
  <header>
    <div class="nav">
      <div class="nav_bar">
        <div class="logo">
          <nuxt-link to="">
            <img src="./../assets/images/JOB.TM.png" alt="" />
          </nuxt-link>
        </div>
        <div class="link">
          <div class="home">
            <nuxt-link to="">
              <img src="./../assets/images/home.svg" alt="" />
            </nuxt-link>
          </div>
          <ul>
            <li class="active">Applicants</li>
            <li>For Employers</li>
            <li>News</li>
          </ul>
        </div>
        <div class="lang">
          <div class="sign_up">
            <ul>
             <nuxt-link to="/login"><li>Sign in</li></nuxt-link>
             <nuxt-link to="/registration"><li>Registration</li></nuxt-link>
            </ul>
          </div>
          <div class="hr"></div>
          <div class="svg">
            <img src="./../assets/images/en.svg" alt="">
           <button><span>En</span></button>
            <svg
              width="11"
              height="8"
              viewBox="0 0 11 8"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M9.57031 1.5L5.2846 6.5L0.998884 1.5L9.57031 1.5Z"
                fill="#484848"
                stroke="#484848"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style>
</style>