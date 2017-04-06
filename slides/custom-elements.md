#### Custom element selectors
```typescript
@Component({selector: 'ow-hero-list'})
@Component({selector: 'ow-hero'})
@Component({selector: 'ow-cancel-button'})
```

#### That we use all over
```html
<h2>Playable Heroes</h2>
<ow-hero-list heroType="support">
  <ow-hero *ngFor="let hero of supportHeroes" 
           [hero]="hero"></ow-hero>
</ow-hero-list>
<footer>
  <ow-cancel-button>Go Back</ow-cancel-button>
</footer>
```
<p>
  <span class="fragment current-only" data-code-focus="5-8,10"></span>
</p>
