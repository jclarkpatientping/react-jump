# react-jump
Jump component is based on jump.js for React


## Installation

```bash
npm install react-jump
```

## Usage

```jsx
import { BackToTop, Jump } from 'react-jump';

const App => () =>
  <div>
      // back to top 跳回顶部
      <BackToTop
      options={{offset: 50}}
      className='cars'
      showHeight={400}
      >
        <button>UP</button>
      </BackToTop>
      // Jump to where you want to go on this page 跳到你想去的地方
      <Jump target={'.cars'}><span style={{color: 'red'}}>i want to go cars</span></Jump>
  </div>

export default App
```
