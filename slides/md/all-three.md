#### CardListComponent <span class="a-decision">(decision)</span>
```typescript
export class CardListComponent {
  cards = [ ... ];
  upvote(card) { ... }
}
```
#### CardComponent <span class="a-presentation">(presentation)</span>
```typescript
export class CardComponent {
  @Input() card;
  @Output() upvote = new EventEmitter();
}
```
#### UpvoteComponent <span class="a-presentation">(presentation)</span>
```typescript
export class UpvoteComponent {
  @Output() upvote = new EventEmitter();
}
```
<span class="fragment current-only" data-code-focus="3"></span>
<span class="fragment current-only" data-code-focus="10"></span>
<span class="fragment current-only" data-code-focus="7"></span>
