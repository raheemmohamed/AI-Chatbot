# AI Chatbot

## Configuration

**1: Import styles to your `.html`**

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/raheemmohamed/AI-Chatbot/dist/v2.1/css/style.css"
/>
```

**2: Add following script tag and Configurations**

```javascript
<script src="https://cdn.jsdelivr.net/gh/raheemmohamed/AI-Chatbot/dist/v2.1/main.js"></script>
<script>
  // Configuration for chatbot
  chatbot.setChatBotConfiguration({
    apiKey: "YOUR-API-KEY",
    chatbotTitle: "YOUR-CHATBOT-TITLE",
    initialMessage: "YOUR-INITIAL-CHATBOT-MESSAGE",
    brandImage:
      "YOUR-BRAND-IMAGE-FOR-CHATBOT",
    suggestions: [
      "Who is raheem ?",
      "Can i know his skills",
      "where he currently living ?",
    ],
  });
</script>
```

**3: Place below html element in your `.html` body**

```html
<!-- Placeholder for  ChatBot UI-->
<div id="chatbot"></div>
```

**AI Chatbot - theme and script CDN links**

```javascript
// Ai chatbot theme
https://cdn.jsdelivr.net/gh/raheemmohamed/AI-Chatbot/dist/v2.1/css/style.css

// Ai chatbot script
https://cdn.jsdelivr.net/gh/raheemmohamed/AI-Chatbot/dist/v2.1/main.js
```

## AI Chatbot UI Design

Few Screenshots below how AI Chatbot UI looks like

![AI Chatbot UI Suggestion Feature](https://github.com/raheemmohamed/AI-Chatbot/blob/main/dist/v2.1/images/AI-chatbot-suggestion-feature.gif)

![AI Chatbot UI](https://github.com/raheemmohamed/AI-Chatbot/blob/main/dist/v2.1/images/AI-chatbot-UI-demo-new.gif)
