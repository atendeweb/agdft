# ⚽ AgendaFut - Ecossistema de Dados Esportivos

![GitHub repo size](https://img.shields.io/github/repo-size/seuusuario/agendafut)
![GitHub last commit](https://img.shields.io/github/last-commit/seuusuario/agendafut)
![GitHub stars](https://img.shields.io/github/stars/seuusuario/agendafut?style=social)

## 📋 Sobre o Projeto

O **AgendaFut** é um ecossistema completo de atualizações de dados de jogos de futebol que funciona como uma **API REST** automatizada. O sistema extrai informações de fontes confiáveis e as disponibiliza em formato HTML pronto para consumo, facilitando o trabalho de:

- 🎙️ **Transmissores** e narradores esportivos
- 🏟️ **Pub/Sport Bars** e estabelecimentos comerciais
- 📺 **Canais de lives** e streamers
- 📊 **Casas esportivas** e analistas de dados
- 📱 **Aplicativos** e sites esportivos

### 🎯 Funcionalidades Principais

- ✅ Resultados de últimos jogos
- 📅 Próximos jogos por data
- 🏆 Jogos por time/seleção
- 📋 Jogos por campeonato
- 🖼️ **Flyers/Posts** prontos para cada jogo
- 🤖 **Personalização com IA** - adicione sua marca ou informações automaticamente
- 🔄 Atualização automática de dados

## 🚀 Links de Acesso

### 📅 Agenda por Data
Acesse todos os jogos organizados por data:
- **[AgendaFut Online - Data](https://agendafut.online/br)**

### ⚽ Agenda por Time/Seleção
Links diretos para cada time com jogos, resultados e flyers:

#### 🇧🇷 Seleções
- **[Brasil](https://agendafut.online/br/brasil)**

#### 🏴󠁧󠁢󠁥󠁮󠁧󠁿 Série A - Times Brasileiros
- **[Flamengo](https://agendafut.online/br/flamengo)**
- **[Corinthians](https://agendafut.online/br/corinthians)**
- **[Palmeiras](https://agendafut.online/br/palmeiras)**
- **[São Paulo](https://agendafut.online/br/sao-paulo)**
- **[Santos](https://agendafut.online/br/santos)**
- **[Grêmio](https://agendafut.online/br/gremio)**
- **[Internacional](https://agendafut.online/br/internacional)**
- **[Atlético-MG](https://agendafut.online/br/atletico-mg)**
- **[Cruzeiro](https://agendafut.online/br/cruzeiro)**
- **[Bahia](https://agendafut.online/br/bahia)**
- **[Vitória](https://agendafut.online/br/vitoria)**
- **[Athletico-PR](https://agendafut.online/br/athletico-pr)**
- **[Vasco](https://agendafut.online/br/vasco)**
- **[Botafogo](https://agendafut.online/br/botafogo)**
- **[Fluminense](https://agendafut.online/br/fluminense)**

#### 🏴󠁧󠁢󠁥󠁮󠁧󠁿 Mais Times (em breve)
- *Novos times sendo adicionados constantemente*

## 📦 Como Usar

### Para Consumir a API
Os dados estão disponíveis em formato HTML estruturado, facilitando a extração e integração com seu sistema:

```html
<!-- Exemplo de estrutura retornada -->
<div class="jogo">
  <div class="time-casa">Flamengo</div>
  <div class="time-visitante">Corinthians</div>
  <div class="data">26/07/2026</div>
  <div class="horario">21:30</div>
  <div class="campeonato">Brasileirão Série A</div>
  <div class="flyer">[Imagem do Flyer]</div>
</div>
