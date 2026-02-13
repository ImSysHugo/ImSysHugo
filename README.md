Um pouco sobre mim... 🚀

```javascript
const dev = {
  nome: "Hugo Miguel Moura",
  idade: 20,
  localizacao: {
    pais: "Portugal",
    cidade: "Amarante"
  },
  especialidades: [
    "Desenvolvimento Web",
    "Design Web",
    "Programação Java (Plugins de Minecraft)"
  ],
  contato: "contacto.hugomoura@gmail.com"
};

console.log(`Olá! Eu sou ${dev.nome}, tenho ${dev.idade} anos e sou do ${dev.localizacao.cidade}, ${dev.localizacao.pais}.`);
console.log("Trabalho com:");
dev.especialidades.forEach((skill, i) => console.log(`  ${i + 1}. ${skill}`));
```
