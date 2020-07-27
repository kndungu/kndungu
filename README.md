```typescript
type GreetingMessage = 'Hello World!' | 'Habari dunia!' | 'Uhoro the!';

const greet = (possibleGreetings: GreetingMessage[]) => {
  const message = possibleGreetings[Math.floor(Math.random() * possibleGreetings.length)];
  console.log(message);
} 

greet(['Hello World!', 'Habari dunia!', 'Uhoro the!']);
```
