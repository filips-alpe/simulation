```typescript
class Particle {}
class Wave {
  public observe() {
    return new Particle().observe()
  }
}
```
