#### CardComponent <span class="a-presentation">(presentation)</span>
```typescript
@Component({
  selector: 'ow-card',
  template: `<h2>{{card.name}}</h2>
    <button (click)="upvote.emit()"></button>`
})
export class CardComponent {
  @Input() card;
  @Output() upvote = new EventEmitter();
}
```
<span class="fragment current-only" data-code-focus="4"></span>
