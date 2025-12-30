# Dishonored 1 - Tradução PT-BR (IA DeepSeek)

Este projeto apresenta uma tradução completa dos textos de **Dishonored 1** para Português do Brasil. A tradução foi realizada de forma automatizada utilizando a API da IA **DeepSeek**, com foco em preservar termos técnicos do jogo e manter a ambientação original. 

## 📋 Conteúdo Traduzido
- Diálogos e legendas de missões. 
- Documentos, livros e notas encontrados pelo mundo. 
- Descrições de itens, melhorias de Piero e inventário. 
- Interface do usuário (HUD) e menus. 

## ⚠️ Requisito Importante
Esta tradução foi baseada nos arquivos originais em inglês (pasta **INT**). Para que ela funcione, seu jogo deve estar configurado para o idioma inglês nas propriedades da Steam/Epic Games.

---

## 🚀 Passo a Passo: Instalação

### 1. Faça o Backup (Segurança)
Antes de qualquer alteração, é essencial salvar os arquivos originais:
1. Vá até a pasta onde o jogo está instalado. O caminho comum é:  
   `C:\Program Files (x86)\Steam\steamapps\common\Dishonored\DishonoredGame\Localization`
2. Clique com o botão direito na pasta **INT** e selecione "Copiar".
3. Cole em um local seguro (ex: sua Área de Trabalho) com o nome `INT_Backup`.

### 2. Aplicar a Tradução
1. Baixe os arquivos deste repositório.
2. Copie a pasta **INT** que você baixou aqui no GitHub.
3. Vá até a pasta de localização do jogo:  
   `...\Dishonored\DishonoredGame\Localization`
4. Cole a pasta **INT** baixada e, quando o Windows perguntar, selecione **"Substituir os arquivos no destino"**.

### 3. Verificar no Jogo
Abra o jogo. Os textos de interação (como "`GBA_Use` Pegar"), objetivos e menus já devem aparecer em português. 

---

## 🛠️ Detalhes Técnicos
- **Codificação:** Os arquivos foram salvos em `UTF-16 LE com BOM` para garantir que acentos e caracteres especiais apareçam corretamente sem erros de fonte. 
- **Preservação de Tags:** Comandos internos como `` `GBA_Use` `` ou `%s` foram mantidos intactos para não quebrar a funcionalidade dos ícones e variáveis do jogo. 

## ⚖️ Créditos
- Tradução gerada via script Python utilizando a API do **DeepSeek**.
- Revisão técnica de tags e variáveis por [Jorge Dorio](https://github.com/JorgeDorio).
