# Components-
Make Header.tsx and About.tsx in Next.js, 2nd Assignment

code of page.tsx file>>>

 import About from "./components/About"
import Header from "./components/Header"


export default function Home(){
  return(
  <>
  <center>
    <main>
      <h1>HOME PAGE</h1>
    </main>
  </center>
  
  <Header />
  <About />
  </>
  ) 
  }

  Now, make a folder of Components and then make file in this folder of Header.tsx and About.tsx and write following code:
  
>>Code of Header.tsx file:

export default function Header(){
    return(
    <>
    
    <h1 style={{background:"LightBlue"}}>--This is Header </h1>
    
    
    </>
    ) 
    }

>>Code of About.tsx file:

export default function About() {
 return(
    <>
        <h2 style={{backgroundColor:"LightGray"}}>--This is About</h2>
    
    
    </>
  )  
}

Now, open terminal and run command of (npm run dev); your code has successfully completed!!!!!
  
