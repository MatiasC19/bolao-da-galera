# 🏆 Bolão da Galera — Copa do Mundo 2026

Site para organizar o bolão da Copa do Mundo FIFA 2026 entre amigos. Cada pessoa entra, escolhe os jogos e registra o palpite de placar exato. Quem acerta o placar exato leva o prêmio daquele jogo.

🔗 **Link do site:** [matiasc19.github.io/bolao-da-galera](https://matiasc19.github.io/bolao-da-galera/)

> Se o link ainda não estiver no ar, veja a seção "Como publicar" abaixo — leva 1 minuto para ativar.

---

## 📋 Como funciona

- **Sem cadastro de senha para os participantes** — qualquer pessoa com o link pode entrar, digitar o nome e registrar o palpite.
- **Cada palpite vale R$ 10.** Quem acerta o **placar exato** leva o valor apostado pelos demais participantes naquele jogo (dividido entre os vencedores, se houver mais de um acerto exato).
- **Só vale placar exato** — não existe sistema de pontos parciais. Ou você acerta o placar (e ganha), ou não acerta.
- **Prazo por jogo** — o admin define uma data e hora limite para cada partida. Depois desse horário, ninguém mais consegue registrar ou alterar o palpite daquele jogo.
- **Resultado oficial** — só o admin insere o placar final de cada jogo. O sistema identifica automaticamente quem acertou e destaca o(s) ganhador(es) com troféu dourado na lista.

## 🔐 Acesso de administrador

A área "Admin" é protegida por senha. Lá você pode:
- Cadastrar os jogos (seleção da casa, visitante, fase do torneio, e prazo limite)
- Inserir, atualizar ou apagar o resultado oficial de cada partida
- Remover jogos ou participantes, se necessário

> A senha de admin está definida no código-fonte (arquivo `index.html`, constante `ADMIN_PW`). Troque para uma senha pessoal antes de divulgar o link, se quiser mais segurança.

## 🌍 Seleções disponíveis

O site já vem com as 48 seleções participantes da Copa do Mundo 2026 (sede: Estados Unidos, Canadá e México), com bandeiras e nomes em português.

## 🛠️ Tecnologia

Projeto 100% estático — um único arquivo `index.html` com HTML, CSS e JavaScript puro (sem frameworks, sem backend, sem build). Os dados (jogos, palpites, participantes) são salvos no `localStorage` do navegador de quem acessa.

> **Importante:** como os dados ficam salvos localmente em cada navegador, os palpites registrados por uma pessoa só aparecem para ela mesma. Para um bolão real entre amigos, o ideal é todos acessarem sempre pelo mesmo link publicado (veja abaixo), e manter o navegador sem limpar o cache/dados do site durante a Copa.

## 🚀 Como publicar (GitHub Pages)

Este repositório já está pronto para o GitHub Pages. Para ativar:

1. Vá em **Settings → Pages** neste repositório
2. Em "Source", selecione a branch **main** e a pasta **/ (root)**
3. Clique em **Save**
4. Em cerca de 1 minuto, o site estará disponível em:
   `https://matiasc19.github.io/bolao-da-galera/`

Esse é o link que você compartilha com seus amigos.

## 📁 Estrutura do projeto

```
.
├── index.html      # Aplicação completa (HTML + CSS + JS)
├── README.md       # Este arquivo
└── docs/
    └── REGRAS.md   # Regras detalhadas do bolão
```

## 📜 Licença

Projeto pessoal, de uso livre entre amigos. Sem fins comerciais.
