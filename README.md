# naabu-x6
Using naabu as a labrary.

```
ip string and single 
threamnum int
ports string nmap syntax (80,443、1-8080、-)
```

```
func main() {
	ip = "127.0.0.1"
	threadnum = 3
	ports = "135,445"
	err, rets := PortScan(ip, threadnum, ports)
	if err != nil {
		log.Fatal(err)
	}
	fmt.Printf("%v\n", rets)
}
```
