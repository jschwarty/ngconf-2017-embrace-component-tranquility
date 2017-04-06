#### CardListComponent <span class="a-decision">(decision)</span>
```typescript
@Component({
  selector: 'ow-card-list',
  template: `<ow-card 
                *ngFor="let card of cards" 
                [card]="card" 
                (upvote)="upvote(card)">
             </ow-card>`
})
export class CardListComponent {
  cards = [ ... ];
  upvote(card) { ... }
}
```
<span class="fragment current-only" data-code-focus="3-7"></span>
<span class="fragment current-only" data-code-focus="10-11"></span>
<span class="fragment current-only" data-code-focus="4-6"></span>
