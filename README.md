# typescript_cheat_sheet
## 🚀 Did you know that you can declare anonymous and named types in TypeScript?

### Here's a guide that highlights the similarities, differences, and use cases of declaring anonymous types and named types in TypeScript:

---


Anonymous Type:
```typescript
let user: { name: string; age: number } = { name: "dammyhack", age: 23 };
console.log(user.age); // Output: 23
```

Named Type:
```typescript
type Person = { name: string; age: number };
let user: Person = { name: "Paul", age: 25 };
console.log(user.age); // Output: 25
```

Similarities:
- Both declare object types with specified properties and their types.
- Provide type safety and enforce structure.

Differences:
- Anonymous types are declared inline where they're used, while named types have a defined name.
- Named types promote code reuse and readability.

Use Cases:
- Use anonymous types for simple, one-off type annotations directly where needed.
- Use named types for reusable type definitions across your codebase, promoting maintainability.

## 🚀


For more insights on TypeScript, follow [Adeyemi Paul](https://twitter.com/dammyhack).


