# naabu-x6
Using naabu as a labrary.


```
func main() {
	err, rets := PortScan("127.0.0.1", 3, "135,445")
	if err != nil {
		log.Fatal(err)
	}
	fmt.Printf("%v\n", rets)
}
```
