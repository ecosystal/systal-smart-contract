# 🪙 Systal Coin (SYST) - Documentação Oficial

> Criptomoeda BEP20 desenvolvida com foco em transparência, segurança e utilidade real no ecossistema da BNB Smart Chain.

---

## 🧱 Sobre o Projeto

O **Systal Coin (SYST)** é o núcleo de um ecossistema moderno, seguro e transparente. Criado com as melhores práticas de contratos inteligentes, o projeto combina:

- ✅ Controle de acesso e desbloqueios temporizados
- ✅ Proteção anti-bot nos 2 minutos iniciais
- ✅ Auditoria pública via NatSpec e verificação em block explorers
- ✅ Compatibilidade com carteiras populares como MetaMask, Trust Wallet, Trezor e Ledger
- ✅ Usabilidade em DEXs (exchanges descentralizadas)

---

## 🪙 Informações do Token

| Campo              | Valor               |
|--------------------|---------------------|
| Nome               | Systal Coin         |
| Símbolo            | SYST                |
| Decimais           | 4                   |
| Supply Máximo      | 100.000.000 SYST    |
| Rede               | BNB Smart Chain     |
| Padrão             | BEP20               |

---

## 🔐 Funcionalidades Técnicas

### 🧷 Mint Controlado
- Mint único via `mintInitialSupply()`
- Alocações com datas de desbloqueio (vesting)
- Whitelist automática para carteiras de destino

### 🔥 Burn
- Qualquer usuário pode queimar seus tokens com `burn(amount)`
- Redução direta do `totalSupply`

### ⛑️ Resgate de Tokens
- `rescueTokens()` e `rescueETH()` para recuperar ativos enviados por engano
- Proteção com `rescueExempt`
- Endereço de resgate configurável

### ⚠️ Anti-Bot
- Bloqueio de transações de contratos não-whitelisted nos primeiros 2 minutos
- Previne ataques de sniping e bots automatizados

---

## 🛠️ Funções Administrativas

- Pausar e retomar transferências (`pause()`)
- Gerenciar whitelist individual ou múltipla
- Atualizar datas de desbloqueio
- Renunciar ou transferir propriedade
- Congelar propriedade (irreversível)
- Gerenciar carteira de resgate
- Marcar tokens como protegidos

---

## 📊 Tokenomics

- **50%** Liquidez
- **25%** Marketing e Equipe
- **25%** Comunidade e Recompensas

O token é usado para:
- Acessar recursos internos e benefícios
- Bonificações e recompensas
- Participação em decisões da comunidade
- Cashback funcional dentro do ecossistema EcoSystal

---

## 🔍 Auditoria e Transparência

- Código 100% público e documentado com NatSpec
- Pronto para verificação em block explorers (ex: BscScan)
- Estrutura amigável para análise por auditores e comunidade

---

## 🌐 Links Úteis

- [📄 Whitepaper (em breve)](https://github.com/seuusuario/systal-smart-contract)
- [🔍 BscScan](https://bscscan.com/token/0x...)
- [📊 Dextools](https://www.dextools.io/app/en/bnb/pair-explorer/0x...)
- [💬 Telegram](https://t.me/SystalCoin)
- [🐦 Twitter / X](https://twitter.com/SystalCoin)

---

## ⚠️ Observação

> O Systal Coin é um **utility token**. Não representa promessa de lucro, valor mobiliário ou participação societária. É voltado exclusivamente para fins funcionais no ecossistema do projeto.

---

## 📜 Licença

Código sob licença MIT. Uso livre com atribuição.

---

## 🤝 Contribuições

Pull Requests são bem-vindos! Para sugestões ou melhorias, abra uma [issue](https://github.com/seuusuario/systal-smart-contract/issues).

