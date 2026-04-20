```typescript
import { match } from 'ts-pattern'

const egor = match('@egorcod')
  .with('@egorcod', () => ({
    location: 'Saint Petersburg · 2026-04-20',
    role:     'AQA Engineer & Developer',
    company:  'Haiku',
    language: 'TypeScript',
    content:  ['t.me/egorcod', '@egorcod'],
  }))
  .exhaustive()
```

---

Building and testing software.

Making content about IT. Helping beginners find their path in tech.
Community founder.

`t.me/egorcod` · `@egorcodd`
