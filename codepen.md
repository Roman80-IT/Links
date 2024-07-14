https://codepen.io/

[Новий запис](https://codepen.io/pen/)

### Як додати React і ReactDOM як зовнішні ресурси?

Ось кроки, як це зробити:

**1. Додайте React і ReactDOM до вашого проекту:**

Відкрийте ваш проект у **CodePen**.
Перейдіть до налаштувань вашого проекту (натисніть на іконку налаштувань на панелі **JS**).

**2. Додайте зовнішні ресурси:**

У вікні налаштувань JS знайдіть розділ "Add External Scripts/Pens".
Додайте наступні URL-адреси для React і ReactDOM:
Для React: https://unpkg.com/react@17/umd/react.development.js
Для ReactDOM: https://unpkg.com/react-dom@17/umd/react-dom.development.js
Якщо використовуєте production версію, можна використовувати наступні URL-адреси:
Для React: https://unpkg.com/react@17/umd/react.production.min.js
Для ReactDOM: https://unpkg.com/react-dom@17/umd/react-dom.production.min.js

**3. Збережіть налаштування і поверніться до вашого коду.**

**4. Імпортуйте React у вашому коді (у випадку TypeScript):**

```typescript
// У CodePen, імпортувати React і ReactDOM явно не потрібно після додавання скриптів
// просто починайте використовувати React
const App = () => {
  return (
    <div>
      <h1>Hello, React with TypeScript in CodePen!</h1>
    </div>
  );
};

ReactDOM.render(<App />, document.getElementById("root"));
```

**5. Додайте HTML елемент з `id="root"` у вашому HTML коді:**

```html
<div id="root"></div>
```

Після цих кроків `CodePen проект` повинен працювати з `React` і `ReactDOM` без проблем.

## youtube

https://www.youtube.com/playlist?list=PLd80C6PYpI-AnA6O9tYwS9gUrQfoVZ41k

[Codepen: обзор и полезные советы по использованию](https://www.youtube.com/watch?v=CIWf_pwUfoc)

## Аккаунти

https://codepen.io/Hyperplexed

https://codepen.io/goit-academy
