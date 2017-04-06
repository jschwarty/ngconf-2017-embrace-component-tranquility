#### ❤️️ &nbsp;&nbsp; Component &nbsp;&nbsp; ❤️️
```typescript
@Component({
  selector: 'ow-upvote-button',
  template: `<button (click)="upvote.emit(hero)"></button>`,
  styles: [`button { border-radius: 50%; }`]
})
export class UpvoteButtonComponent {
  @Input() hero;
  @Output() upvote = new EventEmitter();
}
```
<p>
  <span class="fragment current-visible" data-code-focus="4"></span>
  <span class="fragment current-visible" data-code-focus="7-8"></span>
</p>
