# Amir Abokhssan

## Contact Information
 - **Phone**: +7-911-726-77-23
 - **E-mail**: a.abokhssan@yandex.ru
 - **GitHub**: [a-abokhssan](https://github.com/a-abokhssan)
 - **Twitter**: [acypamir](https://twitter.com/acypamir)
 - **Telegram**: [Amir A.](https://t.me/a_abokhssan)

## About Me
I am 26 years old, I have been trying to become a developer for some time. I have little experience in this field, worked for Vericheck for six months and developed a web application and a chatbot.

## Skills
 - **HTML**
 - **CSS**
 - **JS**
 - **Ruby**
 - **Node**
 - **Express**
 - **Mongo**
 - **React**
 - **Git**

## Code Example

```javascript
import React, { useEffect } from 'react'
import { useDispatch } from 'react-redux'
import Header from './header'
import Cards from './cards'
import { getProducts, getRates } from '../redux/reducers/products'

const Home = () => {
  const dispatch = useDispatch()
  useEffect(() => {
    dispatch(getProducts())
    dispatch(getRates())
  }, [])
  return (
    <div>
      <Header />
      <Cards />
    </div>
  )
}

Home.propTypes = {}

export default Home
```

## Education
 - **North-West Institute of Managment**
 - **Udemy**
 - **Hexlet**
 - **SkillCrucial**

## Languages

 - **Russian** - native
 - **English** - A2
 - **French** - A1

