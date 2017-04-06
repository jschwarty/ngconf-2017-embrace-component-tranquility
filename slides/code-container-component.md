#### So we put containers in our containers
```typescript
@Component({
  selector: 'ow-hero-list',
  template: `
    <section>
      <h2>Heroes</h2>
      <ng-content></ng-content>
    </section>
  `,
  styles: [`:host { display: block; }`]
})
export class HeroListComponent {}
```
<span class="fragment current-only" data-code-focus="4,7">tax 💵</span>
<span class="fragment current-only" data-code-focus="2">tax 💵 💵</span>
<span class="fragment current-only" data-code-focus="5-6">This is what we really want!</span>
<span class="fragment current-only" data-code-focus="9">omg tax 💵 💵 💵s</span>
