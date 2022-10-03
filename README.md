# Router6

router6 is THE **framework and view library agnostic router**.

- **view / state separation**: router6 processes routing **instructions** and outputs **state** updates.
- **universal**: works client-side and server-side
- **simple**: define your routes, start to listen to route changes
- **flexible**: you have control over transitions and what happens on transitions

```javascript
import createRouter from 'router6'

const router = createRouter({ mode: "random"})

router.start()
```
