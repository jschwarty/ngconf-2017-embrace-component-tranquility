```html
<section owHeroList> . . . </section>
```
#### Component footprint gets smaller
```typescript
@Component({
  selector: '[owHeroList]',
  template: `
      <h2>Heroes</h2>
      <ng-content></ng-content>
  `
})
export class HeroListComponent {}
```
