<template>
  <section class="frame-group">
    <div class="frame-container">
      <div class="bem-vido-ao-tutilabs-parent">
        <div class="bem-vido-ao-tutilabs-container">
          <p class="bem-vido-ao">Bem-vido ao</p>
          <p class="tutilabs">Tutilabs</p>
        </div>

        <img class="frame-child hands-move" loading="lazy" alt="" src="/group-2.svg" />
      
      </div>
      <div class="ol-agradecemos-seu-interesse-wrapper">
        <div class="ol-agradecemos-seu-container">
          <p class="ol">Olá,</p>
          <p class="agradecemos-seu-interesse">
            Agradecemos seu interesse em estagiar na Tutiplast e por participar
            do nosso teste de front-end. Este teste foi desenvolvido para
            avaliar suas habilidades e conhecimentos na área, portanto, não se
            preocupe se não conseguir completar todas as tarefas. O objetivo é
            entender seu processo de resolução de problemas e seu conhecimento
            técnico.
          </p>
        </div>
      </div>
      <div class="frame-wrapper">
        <div class="tipo-de-teste-parent">
          <b class="tipo-de-teste">Tipo de teste</b>
          <div class="button-parent">
            <button class="button1">
              <div class="front-end-wrapper">
                <div class="front-end">front-end</div>
              </div>
              <img class="vector-icon" alt="" src="/vector-4.svg" />
              <img class="vector-icon1" alt="" src="/vector.svg" />
            </button>
            <button class="button">
              <div class="front-end-container">
                <div class="back-end">back-end</div>
              </div>
              <img class="vector-icon2" alt="" src="/vector.svg" />
              <img class="vector-icon3" alt="" src="/vector-1.svg" />
            </button>
          </div>
        </div>
      </div>
      
    </div>
    <div class="rectangle-parent">
      <div class="frame-item" />
      <img
        class="mask-group-icon"
        loading="lazy"
        alt=""
        src="/mask-group.svg"
      />
    </div>
  </section>
</template>
<script lang="ts">
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "FrameComponent4",
  });
</script>
<style scoped>
  .bem-vido-ao {
    margin: 0;
  }
  .tutilabs {
    margin: 0;
  }
  .bem-vido-ao-tutilabs-container {
    position: absolute;
    top: 0px;
    left: 0px;
    line-height: 110%;
    font-weight: 500;
    display: inline-block;
    width: 100%;
    height: 100%;
  }
  .frame-child {
    position: absolute;
    top: 88.7px;
    left: 322px;
    width: 60px;
    height: 62.9px;
    z-index: 1;
  }
  .bem-vido-ao-tutilabs-parent {
    align-self: stretch;
    height: 168px;
    position: relative;
  }
  .ol {
    margin: 0;
  }
  .agradecemos-seu-interesse {
    margin: 0;
  }
  .ol-agradecemos-seu-container {
    flex: 1;
    position: relative;
    line-height: 110%;
    display: inline-block;
    max-width: 100%;
  }
  .ol-agradecemos-seu-interesse-wrapper {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 0px var(--padding-9xl) var(--padding-7xs);
    box-sizing: border-box;
    max-width: 100%;
    text-align: justify;
    font-size: var(--font-size-2xs);
    color: var(--color-black);
  }
  .tipo-de-teste {
    position: relative;
    line-height: 14px;
    display: inline-block;
    min-width: 81px;
  }
  
  .vector-icon {
    height: 20.5px;
    width: 20.5px;
    position: relative;
    display: none;
    min-height: 21px;
  }
  .vector-icon1 {
    height: 20.5px;
    width: 20.5px;
    position: relative;
  }
  
  .vector-icon2 {
    height: 20.5px;
    width: 20.5px;
    position: relative;
    display: none;
    min-height: 21px;
  }
  .vector-icon3 {
    height: 20.5px;
    width: 20.5px;
    position: relative;
  }
  .button1 {
    cursor: pointer;
    border: none;
    padding: var(--padding-3xs) var(--padding-base);
    background-color: var(--black);
    border-radius: var(--br-5xl);
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-3xs);
  }
  
  .tipo-de-teste-parent {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-4xs);
  }
  .frame-wrapper {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-7xs);
    font-size: var(--font-size-smi-4);
    color: var(--black);
  }
  .frame-container {
    width: 511px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    min-width: 511px;
    max-width: 100%;
  }
  .frame-item {
    align-self: stretch;
    width: 715px;
    position: relative;
    border-radius: var(--br-6xl);
    background-color: var(--color-sandybrown);
    display: none;
    max-width: 100%;
  }
  .mask-group-icon {
    height: 311px;
    flex: 1;
    position: relative;
    max-width: 100%;
    overflow: hidden;
    z-index: 1;
  }
  .rectangle-parent {
    flex: 1;
    border-radius: var(--br-6xl);
    background-color: var(--color-sandybrown);
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    min-width: 465px;
    max-width: 100%;
  }
  .frame-group {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-sm);
    max-width: 100%;
    text-align: left;
    font-size: var(--font-size-57xl-4);
    color: var(--colortext);
    font-family: var(--font-poppins);
  }

  @media screen and (max-width: 1025px) {
    .frame-container {
      flex: 1;
    }

    .frame-group {
      flex-wrap: wrap;
    }
  }
  @media screen and (max-width: 975px) {
    .bem-vido-ao-tutilabs-container {
      font-size: var(--font-size-42xl);
      line-height: 67px;
    }
  }
  @media screen and (max-width: 725px) {
    .frame-container {
      min-width: 100%;
    }

    .rectangle-parent {
      min-width: 100%;
    }
  }
  @media screen and (max-width: 450px) {
    .bem-vido-ao-tutilabs-container {
      font-size: var(--font-size-27xl);
      line-height: 50px;
    }
  }
  .frame-wrapper {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-7xs);
    font-size: var(--font-size-smi-4);
    color: var(--black);
  }
  .tipo-de-teste-parent {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-4xs);
  }
  .tipo-de-teste {
    position: relative;
    line-height: 14px;
    display: inline-block;
    min-width: 81px;
  }
  .button-parent {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-sm-5);
  }
  .button1 {
    cursor: pointer;
    border: none;
    padding: var(--padding-3xs) var(--padding-base);
    background-color: var(--black);
    border-radius: var(--br-5xl);
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-3xs);
  }
  .front-end-wrapper {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-9xs-3) 0px 0px;
  }
  .front-end {
    position: relative;
    font-size: var(--font-size-smi-4);
    line-height: 14px;
    font-family: var(--font-poppins);
    color: var(--bgmain);
    text-align: left;
    display: inline-block;
    min-width: 60px;
  }
  .button {
    cursor: pointer;
    border: 1px solid var(--black);
    padding: var(--padding-5xs) var(--padding-mini);
    background-color: var(--bgmain);
    border-radius: var(--br-5xl);
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-3xs);
  }
  .front-end-container {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-9xs-3) 0px 0px;
  }
  .back-end {
    position: relative;
    font-size: var(--font-size-smi-4);
    line-height: 14px;
    font-family: var(--font-poppins);
    color: var(--black);
    text-align: left;
    display: inline-block;
    min-width: 62px;
  }

  .hands-move{
  transform: rotate(-15deg);
  
  /* CÓDIGO PARA CHAMAR A ANIMAÇÃO */
  -webkit-animation: rodaroda 3s linear alternate 3;
  -moz-animation: rodaroda 3.0s linear infinite;
  -ms-animation: rodaroda 3.0s linear infinite;
  -o-animation: rodaroda 3.0s linear infinite;
  animation: rodaroda 3.0s linear infinite;
}

/* KEY FRAMES PARA FAZER OS GIROS */
@-webkit-keyframes rodaroda {
  0% { -webkit-transform:rotate(-15deg); -moz-transform:rotate(-15deg); -ms-transform:rotate(-15deg); -o-transform:rotate(-15deg); transform:rotate(-15deg); }
	50% { -webkit-transform:rotate(40deg); -moz-transform:rotate(40deg); -ms-transform:rotate(40deg); -o-transform:rotate(40deg); transform:rotate(40deg); }
	
}
@-moz-keyframes rodaroda {
	0% { -webkit-transform:rotate(-15deg); -moz-transform:rotate(-15deg); -ms-transform:rotate(-15deg); -o-transform:rotate(-15deg); transform:rotate(-15deg); }
	50% { -webkit-transform:rotate(40deg); -moz-transform:rotate(40deg); -ms-transform:rotate(40deg); -o-transform:rotate(40deg); transform:rotate(40deg); }
	
}
@-ms-keyframes rodaroda {
	0% { -webkit-transform:rotate(-15deg); -moz-transform:rotate(-15deg); -ms-transform:rotate(-15deg); -o-transform:rotate(-15deg); transform:rotate(-15deg); }
	50% { -webkit-transform:rotate(40deg); -moz-transform:rotate(40deg); -ms-transform:rotate(40deg); -o-transform:rotate(40deg); transform:rotate(40deg); }
	
}
@-o-keyframes rodaroda {
  0% { -webkit-transform:rotate(-15deg); -moz-transform:rotate(-15deg); -ms-transform:rotate(-15deg); -o-transform:rotate(-15deg); transform:rotate(-15deg); }
	50% { -webkit-transform:rotate(40deg); -moz-transform:rotate(40deg); -ms-transform:rotate(40deg); -o-transform:rotate(40deg); transform:rotate(40deg); }
	
}
@keyframes rodaroda {
	0% { -webkit-transform:rotate(-15deg); -moz-transform:rotate(-15deg); -ms-transform:rotate(-15deg); -o-transform:rotate(-15deg); transform:rotate(-15deg); }
	50% { -webkit-transform:rotate(40deg); -moz-transform:rotate(40deg); -ms-transform:rotate(40deg); -o-transform:rotate(40deg); transform:rotate(40deg); }
	
}
</style>
