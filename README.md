# Burry Image
- lib : skeleton
	

```yaml
# html
.bg
.txt
# css
body: flex-col-center
.bg: [ url , pos: ab-0-0, z-index: -1 , filter: blur(0px) ,w&h: calc(100vw + 60px)]
# js
get: txt,bg
set: [num:0]
eve: {
	blur(): {
		- add num by 1
		- if num greater then 99 then stop_interval(inter)
		- render num as txt to show increase
		- use scale[stackoverflow] , as image clears >  txt should fade as well
	},
	setInterval(): {
		- loop every mini-sec 
		
	}
}
```
