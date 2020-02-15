# 1. Bakytzhan Marxov
## 2. Email: bahamarksov@gmail.com
## 3. **Make the World a better place!**
## 4. Skills: 
* Programming
* IoT
## 5. Code examples:
```golang
func AtoiBase(s string, base string) int {
	num := 0
	len := length(s)
	for _, ch := range base {
		if ch == '-' || ch == '+' || counter(base, string(ch)) != 1 || len < 2 {
			return 0

		}

	}

	for _, ch := range s {
		if counter(base, string(ch)) != 1 {
			return 0

		}

	}


	for i := 0; i < len; i++ {
		num = num + (ind(base, string(s[len-i-1]))) * ppower(length(base), i)
	}
	return num

}
```
## 6. Experience:
1. Participation in hackathons
1. Work in the prototyping laboratory

## 7. Education:
1.  Pass online courses html on codeacademy.com
1. Work in the prototyping laboratory
1. Bachelor of Engineering

## 8. Lear