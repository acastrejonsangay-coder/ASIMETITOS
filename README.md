# Asimetitos: Design Your Own Space Mission

A free web game where students build their own satellite, launch it and find out whether their mission succeeds.

▶ **Play:** https://barbozapablo96-ai.github.io/asimetitos/

NASA Space Apps Challenge 2026. Independent educational project; not affiliated with or endorsed by NASA.

## How to play
1. **Choose a mission** in the 3D carousel (CubeSat, Earth observer, space telescope, lunar orbiter or Mars orbiter) and a difficulty level.
2. **Build your spacecraft** from four pieces: a science instrument, power, an antenna and a rocket, each in a small, medium or large size. Four bars (weight, power, money and science) react to every choice, and "mission control" says GO or NO GO in plain words.
3. **Launch** and watch the mission in orbit, with random events such as solar storms.
4. **Get 0 to 3 stars**, tips on which piece to change, and the real NASA mission your design resembles.

The biggest option is rarely the best one: a huge rocket costs too much, and a small antenna cannot reach Mars.

## How it works
Behind the four pieces there is a simplified engineering model that recalculates the mission after every choice:
- Kepler's orbital period;
- eclipse fraction;
- solar power and battery sizing;
- downlink data volume;
- propellant with the rocket equation;
- cost;
- lifetime and reliability.

The rest of the spacecraft (structure, orbit, computer, attitude control, propulsion, thermal control) is chosen automatically for each mission. Every formula can be opened in the game under "¿Cómo se calcula?".

## Run locally
No installation needed: open `index.html` in any modern browser. It works offline and keeps no personal data.

## Files
- `index.html`: the complete game (HTML, CSS and JavaScript in one file, with no libraries).
- `CITATIONS.md`: NASA sources and real missions used.
- `THIRD_PARTY.md`: third-party resources (none).
- `AI_DISCLOSURE.md`: how AI was used.

## License
MIT. See `LICENSE`.

---

### Resumen en español
**Asimetitos** es un juego web gratuito para estudiantes: eliges una misión, armas tu satélite con 4 piezas (ojo científico, energía, antena y cohete), lo lanzas y recibes de 0 a 3 estrellas. Funciona sin internet y sin cuentas. Es un proyecto educativo independiente; no es oficial de NASA.
