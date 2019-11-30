<template>
  <div class="h-screen w-screen">
    <div class="flex flex-col items-center flex-1 h-full justify-center px-4">
      <div class="flex w-full sm:w-3/4 bg-white sm:mx-4" style="height: 500px">
        <div class="hidden md:block md:w-1/2 lg:w-1/2 rounded-r-lg" style="background: url('https://images.unsplash.com/photo-1512295767273-ac109ac3acfa?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80'); background-size: cover; background-position: center center;"></div>
        <div class="flex flex-col w-full md:w-1/2 mx-4">
          <div class="flex flex-col flex-1 justify-center ml-20 md:ml-2 lg:ml-2">
            <h1 class="font-bold text-xl mb-6 text-center hover:text-indigo-400 transition-colors transition-500 transition-linear">Developer + Designer</h1>
           <div class="mb-4 text-xs text-gray-700 font-mono mx-4">
             <p class="hover:line-through cursor-pointer transition-transform transition-500 transition-linear">Designer: “You shouldn’t put icons on every option. This introduces a ‘Hick’s Law’ issue and the user will be way too overwhelmed.”</p>
             <p>👌Engineer: “Every one of these terms can’t be edited inline. That would overload the DOM. We need to have one single modal that opens to edit a term for efficiency.”</p>
           </div>
            <ul class="text-gray-800 text-sm mb-6 ml-4">
              <li class="text-justify mb-4"><span class="font-semibold text-indigo-600 hover:text-indigo-800 transition-colors transition-500 transition-ease-in-out">UX/UI Desing Skills: </span>User experience research, problem statement, user interviews, pain points, customer journey mapping, storyboards, prototyping and <span class="font-semibold">design solution</span></li>
              <li class="text-justify mb-4"><span class="font-semibold text-indigo-600 hover:text-indigo-800 transition-colors transition-500-scroll transition-ease-in-out">Front-End Development: </span>Primary domain focused on the design/UI component layer of an application. Technology: React, Vue, Nuxt, Sass, PostCSS, Styled Components, UI Libraries (Material UI, Materialize, Reactstrap, TailwindCSS, Tachyons, Ant Design), Netlify, Node, Express, Firebase</li>
              <li class="text-justify mb-4"><span class="font-semibold text-indigo-600 hover:text-indigo-800 transition-colors transition-500-scroll transition-ease-in-out">Education: </span> <span class="font-semibold"> Full-Stack Development Bootcamp </span> - Wild Code School (2019), <span class="font-semibold"> React + Redux Course </span> - Fictizia (2019), <span class="font-semibold">Bachelor's Degree in Computer Science and Engineering </span> - Universidad Internacional de Valencia (2019 - present) </li>
              <li class="text-justify mb-4">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><rect width="24" height="24" fill="none" rx="0" ry="0"></rect><path fill-rule="evenodd" clip-rule="evenodd" d="M15.4 12C15.9601 12 16.2401 12 16.454 12.109C16.6422 12.2049 16.7951 12.3578 16.891 12.546C17 12.7599 17 13.0399 17 13.6L17 14.5L17 18.4C17 18.9601 17 19.2401 16.891 19.454C16.7951 19.6422 16.6422 19.7951 16.454 19.891C16.2401 20 15.9601 20 15.4 20H6L3.6 20C3.03995 20 2.75992 20 2.54601 19.891C2.35785 19.7951 2.20487 19.6422 2.10899 19.454C2 19.2401 2 18.9601 2 18.4L2 14V13.6C2 13.0399 2 12.7599 2.10899 12.546C2.20487 12.3578 2.35785 12.2049 2.54601 12.109C2.75992 12 3.03995 12 3.6 12L11.5 12L15.4 12Z" fill="#2249B3"></path><path fill-rule="evenodd" clip-rule="eve nodd" d="M9.33726 5.49999C9.60565 5.49999 9.65835 5.5032 9.70251 5.5138C9.75353 5.52605 9.8023 5.54626 9.84704 5.57367C9.88576 5.5974 9.9253 5.63239 10.1151 5.82217L11.1778 6.88491L11.2073 6.91439C11.351 7.05838 11.4777 7.18533 11.6305 7.27895C11.7647 7.36119 11.911 7.4218 12.064 7.45854C12.2383 7.50037 12.4176 7.50021 12.6211 7.50002L12.6627 7.49999H19.4C19.6883 7.49999 19.8744 7.50038 20.0161 7.51195C20.1519 7.52305 20.2023 7.54189 20.227 7.55449C20.3211 7.60242 20.3976 7.67891 20.4455 7.77299C20.4581 7.79772 20.4769 7.84808 20.488 7.98391C20.4996 8.12558 20.5 8.31171 20.5 8.59999V9.99999C20.3856 9.91422 20.2636 9.83801 20.135 9.77247C19.8388 9.62158 19.5187 9.55867 19.1543 9.5289C18.8004 9.49998 18.3633 9.49998 17.8214 9.49999H17.8H12.2H12.1786C11.6367 9.49998 11.1996 9.49998 10.8457 9.5289C10.4813 9.55867 10.1612 9.62158 9.86503 9.77247C9.39462 10.0122 9.01217 10.3946 8.77249 10.865C8.62159 11.1612 8.55868 11.4813 8.52891 11.8457C8.49999 12.1996 8.5 12.6367 8.5 13.1786V13.2V16.5H6.6C6.31172 16.5 6.12559 16.4996 5.98392 16.488C5.84809 16.4769 5.79773 16.4581 5.77301 16.4455C5.67892 16.3976 5.60243 16.3211 5.5545 16.227C5.5419 16.2023 5.52306 16.1519 5.51196 16.0161C5.50039 15.8744 5.5 15.6883 5.5 15.4V6.59999C5.5 6.31171 5.50039 6.12558 5.51196 5.98391C5.52306 5.84808 5.5419 5.79772 5.5545 5.77299C5.60243 5.67891 5.67892 5.60242 5.77301 5.55449C5.79773 5.54189 5.84809 5.52305 5.98392 5.51195C6.12559 5.50038 6.31172 5.49999 6.6 5.49999H9.33726ZM9.5 16.5L19.4 16.5C19.6883 16.5 19.8744 16.4996 20.0161 16.488C20.1519 16.4769 20.2023 16.4581 20.227 16.4455C20.3093 16.4035 20.3782 16.3397 20.4262 16.2614C20.4331 16.2502 20.4395 16.2387 20.4455 16.227C20.4573 16.2038 20.4746 16.1581 20.4859 16.0406C20.4866 16.0327 20.4873 16.0246 20.488 16.0161C20.4989 15.8833 20.4999 15.7114 20.5 15.4529C20.5 15.4356 20.5 15.418 20.5 15.4V13.2C20.5 12.6317 20.4996 12.2355 20.4744 11.9271C20.4497 11.6245 20.4036 11.4507 20.3365 11.319C20.1927 11.0368 19.9632 10.8073 19.681 10.6635C19.5493 10.5964 19.3755 10.5503 19.0729 10.5256C18.7645 10.5004 18.3683 10.5 17.8 10.5H12.2C11.6317 10.5 11.2355 10.5004 10.9271 10.5256C10.6245 10.5503 10.4507 10.5964 10.319 10.6635C10.0368 10.8073 9.8073 11.0368 9.66349 11.319C9.5964 11.4507 9.55031 11.6245 9.52559 11.9271C9.50039 12.2355 9.5 12.6317 9.5 13.2V16.5ZM8.5 17.5L6.6 17.5H6.58072C6.31715 17.5 6.08977 17.5 5.90249 17.4847C5.70481 17.4686 5.50821 17.4329 5.31902 17.3365C5.03677 17.1927 4.8073 16.9632 4.66349 16.681C4.56709 16.4918 4.53144 16.2952 4.51529 16.0975C4.49998 15.9102 4.49999 15.6828 4.5 15.4193V15.4V6.59999V6.58072C4.49999 6.31715 4.49998 6.08976 4.51529 5.90248C4.53144 5.7048 4.56709 5.50819 4.66349 5.319C4.8073 5.03676 5.03677 4.80729 5.31902 4.66348C5.50821 4.56708 5.70481 4.53143 5.90249 4.51527C6.08977 4.49997 6.31715 4.49998 6.58073 4.49999L6.6 4.49999H9.33726L9.37891 4.49996C9.58236 4.49977 9.76173 4.49961 9.93596 4.54143C10.089 4.57818 10.2353 4.63879 10.3695 4.72103C10.5223 4.81465 10.649 4.9416 10.7928 5.0856L10.8222 5.11507L11.8849 6.17781C12.0747 6.36759 12.1142 6.40258 12.153 6.42631C12.1977 6.45372 12.2465 6.47393 12.2975 6.48617C12.3417 6.49678 12.3944 6.49999 12.6627 6.49999H19.4L19.4193 6.49999C19.6828 6.49998 19.9102 6.49997 20.0975 6.51527C20.2952 6.53142 20.4918 6.56708 20.681 6.66348C20.9632 6.80729 21.1927 7.03676 21.3365 7.319C21.4329 7.50819 21.4686 7.7048 21.4847 7.90248C21.5 8.08976 21.5 8.31714 21.5 8.58071V8.59999V13.1393C21.5 13.1523 21.5 13.1654 21.5 13.1785V13.2V15.4V15.4193C21.5 15.6828 21.5 15.9102 21.4847 16.0975C21.4686 16.2952 21.4329 16.4918 21.3365 16.681C21.1927 16.9632 20.9632 17.1927 20.681 17.3365C20.4918 17.4329 20.2952 17.4686 20.0975 17.4847C19.9219 17.4991 19.7111 17.4999 19.4683 17.5C19.4521 17.5 19.4358 17.5 19.4193 17.5L19.4 17.5L9 17.5H8.5Z" fill="#FCAACF"></path></svg>
                <span class="font-semibold text-indigo-600 hover:text-indigo-800 transition-colors transition-500-scroll transition-ease-in-out">Recent Projects: </span> <a href="https://github.com/AlenaNik" class="font-semibold"> GitHub Account </a></li>


            </ul>
            </div>
    </div>
  </div>
  </div>
  </div>
</template>

<script>


  export default {

  }
</script>

<style scoped>
  body {
    box-sizing: border-box;
    height: 100%;
    background-color: white;
    margin: 0;
    font-family: "Helvetica Neue";
  }
</style>
