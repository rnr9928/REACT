# React 토이 프로젝트
주소: https://yoyo-9109a.web.app/home  

id:test@test.com    
pw:123456

# 로그인 해야 입장가능
![teemo](https://github.com/rnr9928/REACT/assets/97073355/f5826e18-bcf9-47cf-aeaa-e030fbf25919)

```
import useAuth from '../hook/useAuth'
import {Navigate} from 'react-router-dom'

const ProtectRoute = ({children}) => {

    const {currentUser} = useAuth()

  return  currentUser ? children : <Navigate to='/login'/>
```
useAuth로 사용자 정보를 가져옵니다
currentUser가 있을 경우 children를 렌더링하고 
없을 경우 로그인 페이지로 이동합니다


# 문의 게시판

![zz](https://github.com/rnr9928/REACT/assets/97073355/ca7a1501-0dd0-4869-9c3f-a30d4a8413f3)
![zzzz](https://github.com/rnr9928/REACT/assets/97073355/6f904814-5eea-45f9-8810-c66a27b1d45d)

문의 게시판입니다
서버는 파이어베이스를 이용했습니다

파이어베이스는 실시간DB 제공과  인증을 쉽게 할 수 있습니다

#파이어베이스  DB관리
![z](https://github.com/rnr9928/REACT/assets/97073355/fa4d6a43-ce9b-42f4-9b8e-aeb7e8442923)

