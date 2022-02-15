<svelte:head>
  <title>Ai Yukino</title>
</svelte:head>

<div class="flex center">
  <div class="flex column">
    <div
      class="flex justify-end align-end bgColor border-bottom min-height width min-width border-radius padding-right padding-left"
    >
      <div class="flex space-between bgColor-3 min-width-2">
        <div class="bgColor-2 font-size">Jobs</div>
        <div class="bgColor-2 font-size">Math</div>
      </div>
    </div>
    <div class="flex padding-top width bgColor-4">
      <div class="font-size-2">
        Greetings traveler! I am currently a full stack Java student at <a
          href="https://www.techtalentsouth.com/">Tech Talent South</a
        >
        (TTS) funded by its
        <a href="https://www.techtalentsouth.com/graduate-accelerator"
          >Graduate Accelerator Program</a
        >
        and graduating in late December 2021. I previously completed a BSc in Math
        at
        <a href="https://math.utdallas.edu/"
          >The University of Texas at Dallas</a
        > in Spring 2017. This website is a work in progress.
      </div>
    </div>
  </div>
</div>

<style>
  .font-size {
    font-size: 45px;
  }

  .font-size-2 {
    font-size: 20px;
  }

  .bgColor {
    /* background-color: burlywood; */
    background-color: none;
  }

  .bgColor-2 {
    /* background-color: maroon; */
    background-color: none;
  }

  .bgColor-3 {
    /* background-color: mediumpurple; */
    background-color: none;
  }

  .bgColor-4 {
    /* background-color: plum; */
    background-color: none;
  }

  .column {
    flex-direction: column;
  }

  .flex {
    display: flex;
  }

  .justify-end {
    justify-content: end;
  }

  .space-between {
    justify-content: space-between;
  }

  .align-end {
    align-items: flex-end;
  }

  .center {
    justify-content: center;
  }

  .border-bottom {
    border-bottom: 1px solid lightgray;
  }

  .border-radius {
    border-radius: 0px;
  }

  .min-height {
    min-height: 15vh;
  }

  .min-width {
    min-width: 75vw;
  }

  .min-width-2 {
    min-width: 15vw;
  }

  .width {
    width: 70vw;
  }

  .padding-right {
    padding-right: 20px;
  }

  .padding-left {
    padding-left: 20px;
  }

  .padding-top {
    padding-top: 30px;
  }
</style>
