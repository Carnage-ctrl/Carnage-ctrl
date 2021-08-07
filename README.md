<h2> Olá, eu sou o Diego!</h2>

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
<img src="https://komarev.com/ghpvc/?username=Carnage-ctrl&color=red" alt="Carnage-ctrl" /> 

---
