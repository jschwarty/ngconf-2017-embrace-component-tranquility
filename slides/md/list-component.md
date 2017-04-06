#### CardListComponent <span class="a-decision">(decision)</span>
```typescript
export class CardListComponent {
  cards = [];
  
  constructor(private service: CardService) {}
  
  ngOnInit() { 
    this.cards = this.service.getAll();
  }
}
```
#### CardService
```typescript
export class CardService {
  getAll() { ... }
  upvote(id) { ... }
}
```

<span class="fragment current-only" data-code-focus="4"></span>
<span class="fragment current-only" data-code-focus="12"></span>
