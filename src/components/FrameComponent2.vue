<template>
  <header class="frame-header">
    <div class="frame-child5" />
    <div class="tutilabs-logo-3-wrapper">
      <img
        class="tutilabs-logo-3-icon"
        loading="lazy"
        alt=""
        src="/tutilabslogo-3@2x.png"
      />
    </div>
    <button class="subtitle" style="subtitleStyle">
      <a
        class="feito-por-bruno"
        href="https://www.linkedin.com/in/bruno-cmarinho"
        target="_blank"
        >feito por: Bruno marinho</a
      >
    </button>
  </header>
</template>

<style scoped>
  .frame-child5 {
    height: 69px;
    width: 1240px;
    position: relative;
    border-radius: var(--br-8xs);
    background-color: var(--color-lightgray);
    display: none;
    max-width: 100%;
  }
  .tutilabs-logo-3-icon {
    align-self: stretch;
    height: 36px;
    position: relative;
    max-width: 100%;
    overflow: hidden;
    flex-shrink: 0;
    object-fit: cover;
    z-index: 1;
  }
  .tutilabs-logo-3-wrapper {
    width: 88.1px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px 0px var(--padding-11xs);
    box-sizing: border-box;
  }
  .feito-por-bruno {
    position: relative;
    font-size: var(--font-size-sm-5);
    text-decoration: underline;
    line-height: 15px;
    font-family: var(--font-poppins);
    color: var(--colortext);
    text-align: left;
  }
  .subtitle {
    cursor: pointer;
    border: none;
    padding: var(--padding-smi) var(--padding-3xs) var(--padding-smi)
      var(--padding-2xs-4);
    background-color: var(--color-silver);
    border-radius: 3.95px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    white-space: nowrap;
    z-index: 1;
  }
  .subtitle:hover {
    background-color: var(--color-gray-100);
  }
  .frame-header {
    align-self: stretch;
    border-radius: var(--br-8xs);
    background-color: var(--color-lightgray);
    display: flex;
    flex-direction: row;
    align-items: flex-end;
    justify-content: space-between;
    padding: var(--padding-sm) var(--padding-xs-2) var(--padding-sm)
      var(--padding-mid);
    box-sizing: border-box;
    top: 0;
    z-index: 99;
    position: sticky;
    max-width: 100%;
    gap: var(--gap-xl);
  }
</style>
