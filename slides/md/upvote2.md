#### UpvoteComponent <span class="a-presentation">(presentation)</span>
```typescript
export class UpvoteComponent {
  @Input() cardId;
  constructor(private service: CardService) {}
  
  onClick() {
    this.service.upvote(this.cardId);
  }
}
```
<span class="fragment current-only" data-code-focus="3"></span>
<span class="fragment current-only" data-code-focus="2,6"></span>
