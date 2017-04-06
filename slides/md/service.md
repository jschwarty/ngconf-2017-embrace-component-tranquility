#### CardService
```typescript
export class CardService {
  private _cards;
  
  get cards(): Observable<Card> { ... }
  
  upvote(id) { ... }
}
```
