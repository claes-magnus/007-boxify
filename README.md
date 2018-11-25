# boxify for 007

Link to [007 programming language](https://github.com/masak/007)

**syntax:**
boxify([...array-of-string], width-on-sides, horizontal-white-lines-before-and-after);

*The width must be an even integer. If not, it'll get rounded up to the closest even integer.*

**usage:**

```
boxify(["hej","på dig", "GRUFFALON!"], 2, 1);
boxify(["hej","på dig", "GRUFFALON!"], 3, 2);
boxify(["hej","på dig", "GRUFFALON!"], 4, 0);
boxify(["hej","på dig", "GRUFFALON!"], 5, 1);
boxify(["hej","på dig", "GRUFFALON!"], 6, 3);
```

Outputs:
```
╔══════════════╗
║              ║
║  hej         ║
║  på dig      ║
║  GRUFFALON!  ║
║              ║
╚══════════════╝
╔══════════════════╗
║                  ║
║                  ║
║    hej           ║
║    på dig        ║
║    GRUFFALON!    ║
║                  ║
║                  ║
╚══════════════════╝
╔══════════════════╗
║    hej           ║
║    på dig        ║
║    GRUFFALON!    ║
╚══════════════════╝
╔══════════════════════╗
║                      ║
║      hej             ║
║      på dig          ║
║      GRUFFALON!      ║
║                      ║
╚══════════════════════╝
╔══════════════════════╗
║                      ║
║                      ║
║                      ║
║      hej             ║
║      på dig          ║
║      GRUFFALON!      ║
║                      ║
║                      ║
║                      ║
╚══════════════════════╝
```

#### Future features

- centered text (the ground work is already in place with the half-function)
