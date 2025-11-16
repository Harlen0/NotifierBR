# 🔔 Roblox Notification Library

> A simple and modern notification system for Roblox executors

[🇧🇷 Portuguese Version](#-biblioteca-de-notificações-roblox)

---

## 📦 Installation

```lua
local Notify = loadstring(game:HttpGet("YOUR_RAW_LINK_HERE"))()
```

---

## 🚀 Usage

```lua
-- Success (Green)
Notify:Sucesso("Title", "Message", 5)

-- Error (Red)
Notify:Erro("Title", "Message", 5)

-- Warning (Yellow)
Notify:Aviso("Title", "Message", 5)

-- Info (Blue)
Notify:Info("Title", "Message", 5)

-- Default
Notify:Notificar("Title", "Message", 5)

-- Custom Color
Notify:Custom("Title", "Message", 5, Color3.fromRGB(255, 0, 255))

-- Clear All
Notify:LimparTudo()
```

---

## 💡 Examples

```lua
local Notify = loadstring(game:HttpGet("YOUR_RAW_LINK_HERE"))()

-- Basic notifications
Notify:Sucesso("Connected", "Server connection successful!")
Notify:Erro("Failed", "Could not load data")
Notify:Aviso("Warning", "Low health detected")

-- With error handling
local success, err = pcall(function()
    -- your code
end)

if success then
    Notify:Sucesso("Success", "Code executed!")
else
    Notify:Erro("Error", tostring(err))
end

-- Custom colors
Notify:Custom("Special", "Gold notification!", 5, Color3.fromRGB(255, 215, 0))
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
local Notificar = loadstring(game:HttpGet("SEU_LINK_RAW_AQUI"))()
```

---

## 🚀 Como Usar

```lua
-- Sucesso (Verde)
Notificar:Sucesso("Título", "Mensagem", 5)

-- Erro (Vermelho)
Notificar:Erro("Título", "Mensagem", 5)

-- Aviso (Amarelo)
Notificar:Aviso("Título", "Mensagem", 5)

-- Informação (Azul)
Notificar:Info("Título", "Mensagem", 5)

-- Padrão
Notificar:Notificar("Título", "Mensagem", 5)

-- Cor Customizada
Notificar:Custom("Título", "Mensagem", 5, Color3.fromRGB(255, 0, 255))

-- Limpar Tudo
Notificar:LimparTudo()
```

---

## 💡 Exemplos

```lua
local Notificar = loadstring(game:HttpGet("SEU_LINK_RAW_AQUI"))()

-- Notificações básicas
Notificar:Sucesso("Conectado", "Conexão com servidor bem-sucedida!")
Notificar:Erro("Falhou", "Não foi possível carregar dados")
Notificar:Aviso("Atenção", "Vida baixa detectada")

-- Com tratamento de erro
local sucesso, erro = pcall(function()
    -- seu código
end)

if sucesso then
    Notificar:Sucesso("Sucesso", "Código executado!")
else
    Notificar:Erro("Erro", tostring(erro))
end

-- Cores personalizadas
Notificar:Custom("Especial", "Notificação dourada!", 5, Color3.fromRGB(255, 215, 0))
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
