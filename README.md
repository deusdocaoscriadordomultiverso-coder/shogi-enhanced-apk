# ⚔️ SHOGI: Guerra dos Dois Impérios

**Versão Mobile Otimizada para APK** | Totalmente Offline | Sem Bugs | Performance Premium

## 🎮 Características

✅ **100% Offline** - Funciona sem internet  
✅ **APK Pronto** - Prepare com Cordova  
✅ **Sem Loops Infinitos** - Código otimizado  
✅ **IA Real** - Minimax com estratégia  
✅ **Áudio Sintetizado** - Sons dentro do jogo  
✅ **Responsivo** - Mobile-first design  
✅ **Compatível** - Android e iOS  

## 📋 Requisitos

- Node.js 14+
- Cordova CLI
- Android SDK (para APK) ou Xcode (para iOS)

## 🚀 Como Usar

### 1. Preparar Ambiente
```bash
npm install -g cordova
npm install
cordova prepare
```

### 2. Build APK (Android)
```bash
cordova build android
```
APK estará em: `platforms/android/app/build/outputs/apk/debug/app-debug.apk`

### 3. Executar Jogo
```bash
cordova run android
```

### 4. Jogar no Navegador (Teste)
Abra `index.html` em qualquer navegador moderno.

## 🎯 Objetivo do Jogo

Capture o Rei (玉) inimigo em **Xeque-Mate**!

### Regras Principais
- **Peças Capturadas** viram suas e podem ser reinvocadas
- **Promoção** acontece nas 3 fileiras inimigas
- **Movimento** segue as regras tradicionais do Shogi

## 🏗️ Estrutura

```
shogi-enhanced-apk/
├── index.html        (Jogo completo + interface)
├── config.xml        (Configuração Cordova)
├── package.json      (Dependências)
├── README.md         (Este arquivo)
└── www/              (Será criada ao fazer build)
```

## 🔧 Correções Implementadas

1. ✅ Removido loop infinito de renderização
2. ✅ Otimizado cálculo de IA (minimax com alpha-beta)
3. ✅ Melhorado performance de clonagem de board
4. ✅ Fixado problema de promoção opcional
5. ✅ Corrigido cálculo de xeque-mate
6. ✅ Removidas dependências externas
7. ✅ Compatível com Cordova/PhoneGap

## 📱 Plataformas Suportadas

- ✅ Android 5.0+
- ✅ iOS 11+
- ✅ Navegadores modernos (Chrome, Firefox, Safari, Edge)

## 🎨 Temas

- **Império Solar** (Sente) - Cores quentes (ouro/vermelho)
- **Império das Sombras** (Gote) - Cores frias (púrpura/azul)

## 📊 Tamanho

- Arquivo único: ~32KB
- APK (debug): ~25MB
- APK (release): ~12MB

## 🐛 Reportar Bugs

Entre em contato ou abra uma issue no repositório.

## 📜 Licença

Código livre para uso pessoal e educacional.

---

**Desenvolvido com ❤️ para estrategistas de tabuleiro**