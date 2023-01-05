interface Particle {}
interface Wave {}

class OptimizedParticle implements Particle {
  observe() {
    return new Particle(...).observe();
  }
}
