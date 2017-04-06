#### UpvoteComponent <span class="a-presentation">(presentation)</span>
```typescript
@Component({
  selector: 'ow-upvote',
  template: `<button (click)="onClick()"></button>`
})
export class UpvoteComponent {
  @Output() upvote = new EventEmitter();
}
```
<span class="fragment current-only" data-code-focus="6"></span>
