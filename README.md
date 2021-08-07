<h2> Olá, eu sou o Diego!</h2><img src="https://komarev.com/ghpvc/?username=Carnage-ctrl&color=red" alt="Carnage-ctrl" /> 

```typescript
import express from 'express';

class MinhaVida {
  /* Específicações da minha vida */
  public vida: express.Application;
  public PORT: any | number = 8080;
  public pensamento: string;
  
  constructor(pensamento_do_dia: string) {
    this.vida = express();
    this.pensamento = pensamento_do_dia;
    this.startMyLife();
  };
  
  startMyLife(): void {
    this.vida.listen(this.PORT, () => console.log("Diego iniciado..."));
    setTimeout(() => {
    	console.log(`Pensamento do dia: ${this.pensamento}!`);
    }, 1000)
  };
  
};

new MinhaVida("Café");
```

<p align="left">
  <a href="https://github.com/Carnage-ctrl" target="_blank">
    <img align="left" src="https://github-readme-stats.vercel.app/api?username=Carnage-ctrl&theme=react&show_icons=true">
  </a>
</p>

<h2>Linguagens que utilizo constantemente:</h2>
<code><img width="40" src="https://img.icons8.com/color/452/javascript--v1.png"></code>
<code><img width="40" src="https://img.icons8.com/color/452/typescript.png"></code>
<code><img width="40" src="https://iconarchive.com/download/i99610/blackvariant/button-ui-requests-6/iTerm.ico"></code>
<code><img width="40" src="https://img.icons8.com/color/452/c-plus-plus-logo.png"></code>
<code><img width="40" src="https://cdn3.iconfinder.com/data/icons/logos-and-brands-adobe/512/267_Python-512.png"></code>

