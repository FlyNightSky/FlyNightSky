# StreamScribes

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Poppins&weight=700&pause=1000&width=435&lines=Hello+I+am+StreamScribes+I+am+a+programmer+that+started+coding+on+scratch+then+moved+on+to+web-development;I+have+over+1+year+of+knowledge+in+coding+and+over+2+years+in+scratch.)](https://git.io/typing-svg)

<div class="input-wrapper">
  <input aria-label="Ask us anything">
  <span class="placeholder"></span>
</div>

<style>
body {
  display: grid;
  height: 100vh;
  place-items: center;
  width: 100%;
}

.input-wrapper {
  display: block;
  font-family: monospace;
  font-size: 125%;
  width: 50%;
  > input,
  > .placeholder {
    display: block;
    appearance: none;
    width: 100%;
    height: 100%;
    background-color: transparent;
    border: none;
  }
  > .placeholder {
    pointer-events: none;
    @include typed(
      "How many roads must a man walk down before you call him a man?",
      "How many seas must a white dove sail before she sleeps in the sand?",
      "The answer, my friend, is blowin' in the wind",
      1.5,
      (
        caret-width: 2px,
        caret-space: 2px
      )
    );
  }
  > input {
    &:focus,
    &:active {
      + .placeholder {
        display: none;
      }
    }
  }
}
</style>

