<template>
  
  <section class="frame-section">
 
    <nav id="menu"> 
  <ul> 
    <li><a href="#"> <img class="frame-inner" loading="lazy" alt="" src="/sass.png" /> </a></li>
    <li><a href="#"> <img class="frame-inner" loading="lazy" alt="" src="/vue-js-seeklogo.svg" /> </a></li>
    <li><a href="#"> <img class="frame-inner" loading="lazy" alt="" src="/typescript.png" /> </a></li>
    <li><a  href="#"> <img class="frame-inner" loading="lazy" alt="" src="/github-seeklogo.svg"/> </a></li>
    
    <!--  
      <li><a href="#"> <img class="frame-inner" loading="lazy" alt="" src="/html5.svg" /> </a></li>
    <li><a href="#"> <img class="frame-inner" loading="lazy" alt="" src="/js.png" /> </a></li>
    <li><a href="#"> <img class="frame-inner" loading="lazy" alt="" src="/css.png" /> </a></li> --> 
  </ul> 
</nav>

    <div class="rectangle-group">
      <div class="rectangle-div" />
      <div class="node-wrapper">
        <h2 class="node"id="demo">Sass</h2>
      </div>
      <img class="frame-child1" loading="lazy" alt="" src="/vector-21.svg" />
      <div class="frame-div">
        <div class="frame-parent1">
          <div class="lorem-ipsum-dolor-sit-amet-con-wrapper">
            <h3 class="lorem-ipsum-dolor">
              Lorem ipsum dolor sit amet consectetur. Est ac tristique congue at
              nunc. Urna ullamcorper tortor blandit at interdum eget. Ut ipsum
              ut dolor dolor diam in. Pharetra sit ultrices vitae turpis augue
              tempor.
            </h3>
          </div>
          <div class="frame-child2" />
        </div>
      </div>
    </div>
    <div class="rectangle-container">
      <div class="frame-child3" />
      <img class="mask-group-icon1" alt="" src="/mask-group-11@2x.png" />
      <div class="rectangle-parent1">
        <div class="frame-child4" />
        <h3 class="veja-mais-sobre">veja mais sobre nossos sistemas</h3>
        <div class="instance-wrapper">
          <button class="visualizar-parent">
            <div class="visualizar">Visualizar</div>
            <img class="vector-icon4" alt="" src="/vector-4.svg" />
          </button>
        </div>
      </div>
      
    </div>
  </section>
</template>
<script lang="ts">
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "FrameComponent3",
  });
</script>

<style scoped>
  .frame-inner {
    height: 113px;
    flex: 1;
    position: relative;
    max-width: 100%;
    overflow: hidden;
    object-fit: contain;
    min-width: 113px;
  }
  .rectangle-div {
    align-self: stretch;
    height: 311px;
    position: relative;
    border-radius: var(--br-6xl);
    border: 1px solid var(--color-black);
    box-sizing: border-box;
    display: none;
  }
  .node {
    margin: 0;
    position: relative;
    font-size: inherit;
    line-height: 110%;
    font-weight: 700;
    font-family: inherit;
    display: inline-block;
    min-width: 54px;
    z-index: 1;
  }
  .node-wrapper {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-6xl);
  }
  .frame-child1 {
    align-self: stretch;
    position: relative;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
    object-fit: contain;
    margin-top: -1px;
    z-index: 1;
  }
  .lorem-ipsum-dolor {
    margin: 0;
    align-self: stretch;
    position: relative;
    font-size: inherit;
    line-height: 110%;
    font-weight: 400;
    font-family: inherit;
    z-index: 1;
  }
  .lorem-ipsum-dolor-sit-amet-con-wrapper {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-xs) 0px 0px;
    box-sizing: border-box;
    min-width: 229px;
    max-width: 100%;
  }
  .frame-child2 {
    height: 99px;
    width: 5px;
    position: relative;
    background-color: var(--color-gainsboro);
    z-index: 1;
  }
  .frame-parent1 {
    flex: 1;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-3xs);
    max-width: 100%;
  }
  .frame-div {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-4xs) 0px var(--padding-5xl);
    box-sizing: border-box;
    max-width: 100%;
    font-size: var(--font-size-mini);
    color: var(--color-black);
  }
  .rectangle-group {
    width: 400px;
    border-radius: var(--br-6xl);
    border: 1px solid var(--color-black);
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-base) 0px var(--padding-128xl);
    gap: var(--gap-2xs);
    max-width: 100%;
  }
  .frame-child3 {
    position: absolute;
    top: 0px;
    left: 0px;
    border-radius: var(--br-6xl);
    background-color: var(--porple);
    width: 100%;
    height: 100%;
    display: none;
  }
  .mask-group-icon1 {
    position: absolute;
    top: 0px;
    left: 0px;
    width: 295px;
    height: 302px;
    object-fit: cover;
    z-index: 1;
  }
  .frame-child4 {
    width: 284px;
    height: 89px;
    position: relative;
    backdrop-filter: blur(42px);
    border-radius: var(--br-lg);
    background-color: var(--color-whitesmoke-100);
    display: none;
  }
  .veja-mais-sobre {
    margin: 0;
    position: relative;
    font-size: inherit;
    line-height: 18px;
    font-weight: 400;
    font-family: inherit;
    z-index: 3;
  }
  .visualizar {
    position: relative;
    font-size: var(--font-size-smi-4);
    line-height: 14px;
    font-family: var(--font-poppins);
    color: var(--color-white);
    text-align: left;
    display: inline-block;
    min-width: 59px;
  }
  .vector-icon4 {
    height: 15.1px;
    width: 18.2px;
    position: absolute;
    margin: 0 !important;
    top: 7.7px;
    right: 13.9px;
  }
  .visualizar-parent {
    cursor: pointer;
    border: none;
    padding: var(--padding-4xs-3) var(--padding-sm-9);
    background-color: var(--porple);
    width: 112.8px;
    border-radius: 20.14px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    box-sizing: border-box;
    position: relative;
    gap: var(--gap-5xs-7);
    z-index: 3;
  }
  .visualizar-parent:hover {
    background-color: var(--color-lightslategray);
  }
  .instance-wrapper {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px var(--padding-12xs);
  }
  .rectangle-parent1 {
    position: absolute;
    top: 216px;
    left: 5px;
    backdrop-filter: blur(42px);
    border-radius: var(--br-lg);
    background-color: var(--color-whitesmoke-100);
    width: 284px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-sm) var(--padding-7xs) var(--padding-6xs-4);
    box-sizing: border-box;
    gap: var(--gap-xl);
    z-index: 2;
  }
  .rectangle-container {
    height: 311px;
    width: 295px;
    position: relative;
    border-radius: var(--br-6xl);
    background-color: var(--porple);
    font-size: var(--font-size-base);
    color: var(--colortext);
  }
  .frame-section {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-lgi-5);
    max-width: 100%;
    text-align: left;
    font-size: var(--font-size-xl);
    color: var(--black);
    font-family: var(--font-poppins);
  }

  @media screen and (max-width: 450px) {
    .node {
      font-size: var(--font-size-base);
      line-height: 18px;
    }

    .frame-child2 {
      width: 100%;
      height: 5px;
    }

    .frame-parent1 {
      flex-wrap: wrap;
    }
  }
  #menu ul li a { 
    padding: 2px 10px; 
    display: inline-block; /* visual do link */  
    color: #333; 
    text-decoration: none; 
    border-bottom:3px solid #EDEDED; 
    list-style:none;
   
}
#menu ul { padding:0px;
  margin:0px;
  background-color:#EDEDED;
  list-style:none;
  border-radius: var(--br-48xl-6) ;
  background-color:var(--color-lightgray);
}
#menu ul li { display: inline; }

</style>
