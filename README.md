# 🎹 Piano Virtual

Um piano virtual interativo com sons de piano real, desenvolvido com HTML, CSS, JavaScript e Tone.js.

![Piano Virtual](https://img.shields.io/badge/Status-Concluído-success)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=flat&logo=javascript&logoColor=black)
![Tone.js](https://img.shields.io/badge/Tone.js-13B9FD?style=flat)

## ✨ Características

- 🎵 **Sons de Piano Real** - Usa samples do Salamander Grand Piano
- 🎹 **3 Oitavas Completas** - 21 teclas brancas e 15 teclas pretas
- ⌨️ **Controle por Teclado** - Mapeamento intuitivo QWERTY
- 🎚️ **Controle de Volume** - Ajuste o volume do piano
- 🎼 **Alternância de Oitava** - Toque em diferentes registros (C2 até C7)
- 📱 **Responsivo** - Funciona em desktop, tablet e mobile
- 🎨 **Interface Moderna** - Design elegante e intuitivo
- 🔊 **Sustain Natural** - Release suave como um piano real
- 🎛️ **Toggle Notas/Teclas** - Alterne entre mostrar nomes das notas ou atalhos do teclado

## 🚀 Demonstração

[**Experimente o Piano Virtual ao vivo**](https://piano-virtual-orpin.vercel.app/)

## 🎮 Como Usar

### Teclas do Teclado

**Teclas Brancas (Notas Naturais):**
- **Oitava 1:** `Z` `X` `C` `V` `B` `N` `M`
- **Oitava 2:** `Q` `W` `E` `R` `T` `Y` `U`
- **Oitava 3:** `I` `O` `P` `[` `]` `,` `.`

**Teclas Pretas (Sustenidos/Bemóis):**
- **Oitava 1:** `S` `D` `G` `H` `J`
- **Oitava 2:** `2` `3` `5` `6` `7`
- **Oitava 3:** `9` `0` `-` `F` `K`

**Controles:**
- `←` `→` - Mudar oitava
- Mouse/Touch - Clique nas teclas para tocar

### Controles da Interface

- **Toggle Notas/Teclas** - Alterna entre mostrar nomes das notas musicais ou atalhos do teclado
- **Controle de Oitava** - Botões +/- para subir ou descer a oitava base
- **Controle de Volume** - Slider para ajustar o volume geral do piano

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da aplicação
- **CSS3** - Estilização e animações
  - Gradientes personalizados
  - Flexbox para layout responsivo
  - Media queries para diferentes tamanhos de tela
- **JavaScript** - Lógica do piano e interatividade
- **[Tone.js](https://tonejs.github.io/)** - Biblioteca para gerenciamento de áudio
  - Sampler para reprodução de samples
  - Sistema de sustain/release
  - Controle de volume em dB

## 📦 Estrutura do Projeto

```
pianovirtual/
│
├── index.html          # Arquivo principal (HTML + CSS + JS)
├── README.md           # Documentação do projeto
├── .gitignore          # Arquivos ignorados pelo Git
└── vercel.json         # Configuração do Vercel
```

## 🎼 Samples de Áudio

O projeto utiliza os samples do **Salamander Grand Piano**, uma biblioteca gratuita de alta qualidade com gravações de um piano de cauda real. Os samples são carregados automaticamente via CDN do Tone.js.

### Características dos Samples:
- Formato: MP3
- Qualidade: Alta resolução
- Cobertura: A0 até C8
- Release natural e sustain realista

## 🚀 Como Executar Localmente

1. Clone o repositório:
```bash
git clone https://github.com/PietroNozella/PianoVirtual.git
```

2. Navegue até a pasta:
```bash
cd PianoVirtual
```

3. Abra o arquivo `index.html` no seu navegador preferido

Ou simplesmente arraste o arquivo `index.html` para o navegador.

## 🌐 Deploy

Para fazer deploy do projeto, você pode usar:

- **GitHub Pages** - Ative nas configurações do repositório
- **Netlify** - Arraste a pasta para o dashboard
- **Vercel** - Conecte seu repositório GitHub

## 📱 Compatibilidade

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Opera 67+
- ✅ Navegadores mobile modernos

## 🎨 Recursos Visuais

- Interface dark com gradientes suaves
- Teclas com efeitos de hover e active
- Animações fluidas
- Feedback visual ao pressionar teclas
- Loading screen com barra de progresso

## 🔧 Futuras Melhorias

- [ ] Gravação e playback de melodias
- [ ] Metronomo integrado
- [ ] Pedal de sustain virtual
- [ ] Diferentes tipos de piano (upright, electric)
- [ ] Visualização de partituras
- [ ] Modo de aprendizado com tutoriais
- [ ] Exportação de áudio em MP3/WAV

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👤 Autor

**Pietro Nozella**

- GitHub: [@PietroNozella](https://github.com/PietroNozella)
- Email: pietro.nozella@example.com

## 🤝 Contribuições

Contribuições, issues e feature requests são bem-vindos!

Sinta-se à vontade para verificar a [página de issues](https://github.com/PietroNozella/PianoVirtual/issues).

## ⭐ Mostre seu Apoio

Se este projeto te ajudou, dê uma ⭐️!

## 📝 Agradecimentos

- [Tone.js](https://tonejs.github.io/) - Pela excelente biblioteca de áudio
- [Salamander Grand Piano](https://github.com/sfzinstruments/salamander) - Pelos samples de piano de alta qualidade
- Comunidade open source - Por inspiração e recursos

---

Desenvolvido com ❤️ por Pietro Nozella

