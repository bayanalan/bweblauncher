<template>
  <div class="container">
    <div>
     <center><img class="w-72" src="google.svg" /></center> 
      <h1 class="title">
        B web launcher
      </h1>
<h1 class="subtitle">
        the Google launcher.
      </h1>

      <div class="links">
        <a
          href="https://docs.google.com/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          google docs
        </a>
       <a
          href="https://slides.google.com/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          google slides
        </a>

        <a
          href="https://sites.google.com/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          sites
        </a>


<a
          href="https://www.google.com/maps"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          maps
        </a>


<a
          href="https://www.google.com"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          google
        </a>

      

        <a
          href="https://sheets.google.com/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          google sheets
        </a>

        <a
          href="mail.google.com"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Gmail
        </a>


        <a
          href="https://music.youtube.com/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          music
        </a>


        <a
        href="https://chrome.google.com/webstore/category/extensions?utm_source=chrome-ntp-icon"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          web store
        </a>



        <a
          href="https://www.youtube.com/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
        youtube
        </a>


       <a
          href="https://calendar.google.com/calendar"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
        calendar
        </a>


        <a
          href="https://apps.google.com/meet/?utm_source=google&utm_medium=cpc&utm_campaign=na-US-all-en-dr-bkws-all-all-trial-e-dr-1009892&utm_content=text-ad-none-any-DEV_c-CRE_494900468603-ADGP_Desk+%7C+BKWS+-+EXA+%7C+Txt+~+Meet-KWID_43700060639535248-kwd-13506986&utm_term=KW_meet-ST_meet&gclsrc=aw.ds&&gclid=Cj0KCQjwp86EBhD7ARIsAFkgakjUzdI6EQjnUBHMVF6-V8C9Z6IBVylY2_VtWNgfcYL8hx72phgW014aApoYEALw_wcB"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
        meet
        </a>


       <a
          href="https://drive.google.com/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
        drive
        </a>
        

      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
