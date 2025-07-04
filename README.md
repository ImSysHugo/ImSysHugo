Um pouco sobre mim... 🚀

```javascript
const dev = {
  nome: "Hugo Miguel Moura",
  idade: 19,
  localizacao: {
    pais: "Portugal",
    cidade: "Porto"
  },
  empresa: {
    nome: "Volphax Inc.",
    papel: "Co-fundador / Investidor"
  },
  especialidades: [
    "Desenvolvimento Web",
    "Design Web",
    "Programação Java (Plugins de Minecraft)"
  ],
  contato: "contacto.hugomoura@gmail.com"
};

console.log(`Olá! Eu sou ${dev.nome}, tenho ${dev.idade} anos e sou do ${dev.localizacao.cidade}, ${dev.localizacao.pais}.`);
console.log(`Sou um dos donos da empresa ${dev.empresa.nome}, onde atuo como ${dev.empresa.papel}.`);
console.log("Trabalho com:");
dev.especialidades.forEach((skill, i) => console.log(`  ${i + 1}. ${skill}`));
```
