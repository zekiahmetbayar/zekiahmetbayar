```golang
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- 🔭 I’m currently working on":      "HAVELSAN as Software Developer",
		"- 🌱 I’m currently learning":        "Golang, Bash, Python",
		"- 👯 I’m looking to collaborate on": "Golang, Bash, Python related projects",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
	}
}
```

<p align="center">
  <a href="https://dev.to/zeki">
    <img src="https://d2fltix0v2e0sb.cloudfront.net/dev-badge.svg" alt="Zeki Ahmet Bayar's DEV Profile" height="30" width="30">
  </a>

  <a href="https://www.linkedin.com/in/zeki-ahmet-bayar-7a8062173/">
    <img src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" alt="Zeki Ahmet Bayara's LinkedIn Profile" height="30" width="30">
  </a>
</p>
