```typescript
interface Particle {}
interface Wave {}

class Wave implements Particle {
  observe() {
    return new Particle(...).observe();
  }
}
```
