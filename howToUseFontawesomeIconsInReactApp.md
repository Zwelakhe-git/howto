## dependecies
```shell
npm install @fortawesome/fontawesome-svg-core @fortawesome/free-solid-svg-icons @fortawesome/free-regular-svg-icons @fortawesome/free-brands-svg-icons @fortawesome/react-fontawesome
```

## use
```tsx
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome'
import { faHouse, faStar } from '@fortawesome/free-solid-svg-icons'
import { faGithub } from '@fortawesome/free-brands-svg-icons'

function App() {
  return (
    <div>
      {/* Basic usage */}
      <FontAwesomeIcon icon={faHouse} />

      {/* With size and style */}
      <FontAwesomeIcon icon={faStar} size="2x" style={{ color: 'gold' }} />

      {/* Brand icons */}
      <FontAwesomeIcon icon={faGithub} spin />
    </div>
  )
}

export default App
```
