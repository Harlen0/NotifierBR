# 🔔 Roblox Notification Library

> A simple and modern notification system for Roblox executors

[🇧🇷 Portuguese Version](#-biblioteca-de-notificações-roblox)

---

## 📦 Installation

```lua
local NotificarBR = loadstring(game:HttpGet("https://raw.githubusercontent.com/Harlen0/NotifierBR/refs/heads/main/open%20source%20for%20you%20meh"))()
```

---

## 🚀 Usage

```lua
-- Success (Green)
NotificarBR:Sucesso("Title", "Message", 5)

-- Error (Red)
NotificarBR:Erro("Title", "Message", 5)

-- Warning (Yellow)
NotificarBR:Aviso("Title", "Message", 5)

-- Info (Blue)
NotificarBR:Info("Title", "Message", 5)

-- Default
NotificarBR:Notificar("Title", "Message", 5)

-- Custom Color
NotificarBR:Custom("Title", "Message", 5, Color3.fromRGB(255, 0, 255))

-- Clear All
NotificarBR:LimparTudo()
```

---

## 💡 Examples

```lua
local NotificarBR = loadstring(game:HttpGet("https://raw.githubusercontent.com/Harlen0/NotifierBR/refs/heads/main/open%20source%20for%20you%20meh"))()

-- Basic notifications
NotificarBR:Sucesso("Connected", "Server connection successful!")
NotificarBR:Erro("Failed", "Could not load data")
NotificarBR:Aviso("Warning", "Low health detected")

-- With error handling
local success, err = pcall(function()
    -- your code
end)

if success then
    NotificarBR:Sucesso("Success", "Code executed!")
else
    NotificarBR:Erro("Error", tostring(err))
end

-- Custom colors
NotificarBR:Custom("Special", "Gold notification!", 5, Color3.fromRGB(255, 215, 0))
```

---

## 🎨 Color Presets

```lua
Color3.fromRGB(46, 204, 113)   -- Green
Color3.fromRGB(231, 76, 60)    -- Red
Color3.fromRGB(241, 196, 15)   -- Yellow
Color3.fromRGB(52, 152, 219)   -- Blue
Color3.fromRGB(155, 89, 182)   -- Purple
Color3.fromRGB(255, 215, 0)    -- Gold
```

---

## ⭐ Features

- Multiple notification types
- Smooth animations
- Auto-stacking
- Manual close button
- Customizable colors
- Lightweight & fast

---

<br><br>

---

# 🇧🇷 Biblioteca de Notificações Roblox

> Um sistema de notificações simples e moderno para executores Roblox

---

## 📦 Instalação

```lua
local NotificarBR = loadstring(game:HttpGet("https://raw.githubusercontent.com/Harlen0/NotifierBR/refs/heads/main/open%20source%20for%20you%20meh"))()
```

---

## 🚀 Como Usar

```lua
-- Sucesso (Verde)
NotificarBR:Sucesso("Título", "Mensagem", 5)

-- Erro (Vermelho)
NotificarBR:Erro("Título", "Mensagem", 5)

-- Aviso (Amarelo)
NotificarBR:Aviso("Título", "Mensagem", 5)

-- Informação (Azul)
NotificarBR:Info("Título", "Mensagem", 5)

-- Padrão
NotificarBR:Notificar("Título", "Mensagem", 5)

-- Cor Customizada
NotificarBR:Custom("Título", "Mensagem", 5, Color3.fromRGB(255, 0, 255))

-- Limpar Tudo
NotificarBR:LimparTudo()
```

---

## 💡 Exemplos

```lua
local NotificarBR = loadstring(game:HttpGet("https://raw.githubusercontent.com/Harlen0/NotifierBR/refs/heads/main/open%20source%20for%20you%20meh"))()

-- Notificações básicas
NotificarBR:Sucesso("Conectado", "Conexão com servidor bem-sucedida!")
NotificarBR:Erro("Falhou", "Não foi possível carregar dados")
NotificarBR:Aviso("Atenção", "Vida baixa detectada")

-- Com tratamento de erro
local sucesso, erro = pcall(function()
    -- seu código
end)

if sucesso then
    NotificarBR:Sucesso("Sucesso", "Código executado!")
else
    NotificarBR:Erro("Erro", tostring(erro))
end

-- Cores personalizadas
NotificarBR:Custom("Especial", "Notificação dourada!", 5, Color3.fromRGB(255, 215, 0))
```

---

## 🎨 Presets de Cores

```lua
Color3.fromRGB(46, 204, 113)   -- Verde
Color3.fromRGB(231, 76, 60)    -- Vermelho
Color3.fromRGB(241, 196, 15)   -- Amarelo
Color3.fromRGB(52, 152, 219)   -- Azul
Color3.fromRGB(155, 89, 182)   -- Roxo
Color3.fromRGB(255, 215, 0)    -- Dourado
```

---

## ⭐ Características

- Múltiplos tipos de notificação
- Animações suaves
- Empilhamento automático
- Botão para fechar manualmente
- Cores personalizáveis
- Leve e rápido

---
