<script>
  import svelteLogo from "./assets/svelte.svg";
  import devopsCycle from "./assets/devops-cycle.svg";
</script>

<main>
  <div class="bg" />
  <div class="bg bg2" />
  <div class="bg bg3" />

  <section class="flex flex-col lg:flex-row md:flex-col my-8 space-y-8 lg:space-x-12">
    <div class="bg-white max-w-screen-md rounded-md mx-2 pt-8 pb-2 px-8 self-center opacity-95 ">
      <h1 class="text-center font-mono text-3xl">Antonio Arenzana Pulido</h1>

      <img
        class="self-center h-32 my-8 mx-auto"
        src={devopsCycle}
        alt="DevOps Cycle"
      />
      <h2 class="text-center font-mono text-xl">DevOps Engineer</h2>

      <p class="text-center font-fono mt-4 text-lg">
        Currently working on <a class="color-blue" href="https://edpuzzle.com/">EdPuzzle</a> managing
        cloud infrastructure and managing the automation of applications development
        lifecycle
      </p>

      <div class="flex flex-row mt-4 justify-between max-w-xs mx-auto">
        <a href="https://www.linkedin.com/in/antonio-arenzana-pulido"
          ><svg class="w-12 h-24" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg"><defs><style>.cls-1{fill:#007fb5;}.cls-2{fill:#fff;}</style></defs><title/><g data-name="14-linkedin" id="_14-linkedin"><rect class="cls-1" height="64" rx="11.2" ry="11.2" width="64"/><rect class="cls-2" height="32.72" width="9.03" x="8.99" y="23.54"/><path class="cls-2" d="M48.2,23.54C41.54,21,36.72,25.3,34.66,27.7V23.54h-9V56.26h9V39a8.45,8.45,0,0,1,2.23-5.92,4.75,4.75,0,0,1,3.41-1.67A5.42,5.42,0,0,1,44.24,33a6.13,6.13,0,0,1,1.7,4.35V56.26H56.1V36S57.23,26.92,48.2,23.54Z"/><circle class="cls-2" cx="13.5" cy="13.38" r="5.64"/></g></svg></a
        >
        <a aria-label="email" href="mail:antonioarenzanapulido@gmail.com"
          ><svg
            class="w-12 h-24"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
            ><defs
              ><style>
                .cls-3 {
                  fill: #f19b5f;
                }
                .cls-4 {
                  fill: #ffce69;
                }
                .cls-5 {
                  fill: #ed960a;
                }
                .cls-6 {
                  fill: #6c2e7c;
                }
              </style></defs
            ><g id="Icons"
              ><rect
                class="cls-3"
                height="18"
                rx="3"
                width="22"
                x="1"
                y="3"
              /><rect
                class="cls-4"
                height="13"
                rx="3"
                width="22"
                x="1"
                y="3"
              /><path
                class="cls-5"
                d="M15.717,12.029l3.956-3.6a1,1,0,0,0-1.346-1.48L13.35,11.479a2.005,2.005,0,0,1-2.7,0L5.673,6.95A1,1,0,1,0,4.327,8.43l3.957,3.6L4.328,15.62A1,1,0,1,0,5.672,17.1l4.143-3.76a3.937,3.937,0,0,0,4.37,0l4.143,3.76a1,1,0,1,0,1.344-1.48Z"
              /></g
            ><g data-name="Layer 4" id="Layer_4"
              ><path
                class="cls-6"
                d="M20,2H4A4,4,0,0,0,0,6V18a4,4,0,0,0,4,4H20a4,4,0,0,0,4-4V6A4,4,0,0,0,20,2Zm2,16a2,2,0,0,1-2,2H4a2,2,0,0,1-2-2V6A2,2,0,0,1,4,4H20a2,2,0,0,1,2,2Z"
              /><path
                class="cls-6"
                d="M19.74,7.017a1,1,0,0,0-1.413-.067L13.35,11.479a2.005,2.005,0,0,1-2.7,0L5.673,6.95A1,1,0,1,0,4.327,8.43l3.957,3.6L4.328,15.62A1,1,0,1,0,5.672,17.1l4.143-3.76a3.937,3.937,0,0,0,4.37,0l4.143,3.76a1,1,0,1,0,1.344-1.48l-3.955-3.591,3.956-3.6A1,1,0,0,0,19.74,7.017Z"
              /></g
            ></svg
          ></a
        >
        <a href="https://github.com/antonioarenzanapulido"
          ><svg
            class="w-12 h-24"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            ><path
              d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"
            /></svg
          ></a
        >
      </div>
    </div>

    <div class="bg-white max-w-screen-md rounded-md mx-2 p-8 self-center opacity-95 ">
      <h3 class="text-xl text-center">Current goals</h3>
      <ul class="mt-8 space-y-2">
        <li class="flex space-x-2">
          <span class="block w-8 h-8">✅</span>
          <p class="text-lg">AWS Certified Solutions Architect - Associate</p>
        </li>
        <li class="flex space-x-2">
          <svg
            class="animate-spin h-8 w-8"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
            ><path
              d="M6.8042,15A.99956.99956,0,0,0,5.438,14.63379l-1.73242,1a1.00016,1.00016,0,0,0,1,1.73242l1.73242-1A1.00073,1.00073,0,0,0,6.8042,15ZM3.70557,8.36621l1.73242,1a1.00016,1.00016,0,1,0,1-1.73242l-1.73242-1a1.00016,1.00016,0,0,0-1,1.73242ZM6,12a1,1,0,0,0-1-1H3a1,1,0,0,0,0,2H5A1,1,0,0,0,6,12ZM17.1958,9a1.0006,1.0006,0,0,0,1.36621.36621l1.73242-1a1.00016,1.00016,0,1,0-1-1.73242l-1.73242,1A1.00073,1.00073,0,0,0,17.1958,9ZM15,6.8042A1.0006,1.0006,0,0,0,16.36621,6.438l1-1.73242a1.00016,1.00016,0,1,0-1.73242-1l-1,1.73242A1.00073,1.00073,0,0,0,15,6.8042Zm5.29443,8.82959-1.73242-1a1.00016,1.00016,0,1,0-1,1.73242l1.73242,1a1.00016,1.00016,0,0,0,1-1.73242ZM16.36621,17.562a1.00016,1.00016,0,1,0-1.73242,1l1,1.73242a1.00016,1.00016,0,1,0,1.73242-1ZM21,11H19a1,1,0,0,0,0,2h2a1,1,0,0,0,0-2Zm-9,7a1,1,0,0,0-1,1v2a1,1,0,0,0,2,0V19A1,1,0,0,0,12,18Zm-3-.8042a.99954.99954,0,0,0-1.36621.36621l-1,1.73242a1.00016,1.00016,0,0,0,1.73242,1l1-1.73242A1.00073,1.00073,0,0,0,9,17.1958ZM12,2a1,1,0,0,0-1,1V5a1,1,0,0,0,2,0V3A1,1,0,0,0,12,2Z"
              fill="#6563ff"
            /></svg
          >
          <p class="text-lg">Certified Kubernetes Administrator (CKA)</p>
        </li>
        <li class="flex space-x-2">
          <svg
            class="animate-spin h-8 w-8"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
            ><path
              d="M6.8042,15A.99956.99956,0,0,0,5.438,14.63379l-1.73242,1a1.00016,1.00016,0,0,0,1,1.73242l1.73242-1A1.00073,1.00073,0,0,0,6.8042,15ZM3.70557,8.36621l1.73242,1a1.00016,1.00016,0,1,0,1-1.73242l-1.73242-1a1.00016,1.00016,0,0,0-1,1.73242ZM6,12a1,1,0,0,0-1-1H3a1,1,0,0,0,0,2H5A1,1,0,0,0,6,12ZM17.1958,9a1.0006,1.0006,0,0,0,1.36621.36621l1.73242-1a1.00016,1.00016,0,1,0-1-1.73242l-1.73242,1A1.00073,1.00073,0,0,0,17.1958,9ZM15,6.8042A1.0006,1.0006,0,0,0,16.36621,6.438l1-1.73242a1.00016,1.00016,0,1,0-1.73242-1l-1,1.73242A1.00073,1.00073,0,0,0,15,6.8042Zm5.29443,8.82959-1.73242-1a1.00016,1.00016,0,1,0-1,1.73242l1.73242,1a1.00016,1.00016,0,0,0,1-1.73242ZM16.36621,17.562a1.00016,1.00016,0,1,0-1.73242,1l1,1.73242a1.00016,1.00016,0,1,0,1.73242-1ZM21,11H19a1,1,0,0,0,0,2h2a1,1,0,0,0,0-2Zm-9,7a1,1,0,0,0-1,1v2a1,1,0,0,0,2,0V19A1,1,0,0,0,12,18Zm-3-.8042a.99954.99954,0,0,0-1.36621.36621l-1,1.73242a1.00016,1.00016,0,0,0,1.73242,1l1-1.73242A1.00073,1.00073,0,0,0,9,17.1958ZM12,2a1,1,0,0,0-1,1V5a1,1,0,0,0,2,0V3A1,1,0,0,0,12,2Z"
              fill="#6563ff"
            /></svg
          >
          <p class="text-lg" >AWS Certified DevOps Engineer - Professional</p>
        </li>
      </ul>
    </div>
  </section>
</main>

<style>
  .bg {
    animation: slide 3s ease-in-out infinite alternate;
    background-image: linear-gradient(-60deg, #6c3 50%, #09f 50%);
    bottom: 0;
    left: -50%;
    opacity: 0.5;
    position: fixed;
    right: -50%;
    top: 0;
    z-index: -1;
  }

  .bg2 {
    animation-direction: alternate-reverse;
    animation-duration: 4s;
  }

  .bg3 {
    animation-duration: 5s;
  }

  @keyframes slide {
    0% {
      transform: translateX(-25%);
    }
    100% {
      transform: translateX(25%);
    }
  }
</style>
