# Migration of ted.mirawatt.com from Axial servers
On 2018-07-05 I migrated all the data on axial servers
which histed multiple sites. 

Published to: http://ted.mirawatt.com/
Published to: http://daniel-lauzon.com/site-ted.mirawatt.com/

Using CNAME record on mirawatt.com:
```
CNAME ted daneroo.github.io

$ dig ted.mirawatt.com

;; ANSWER SECTION:
ted.mirawatt.com.	713	IN	CNAME	daneroo.github.io.
daneroo.github.io.	3413	IN	CNAME	sni.github.map.fastly.net.
sni.github.map.fastly.net. 3413	IN	A	185.199.108.153
sni.github.map.fastly.net. 3413	IN	A	185.199.109.153
sni.github.map.fastly.net. 3413	IN	A	185.199.110.153
sni.github.map.fastly.net. 3413	IN	A	185.199.111.153

```
## TODO
- redirect DNS, add CNAME
- ~~[Publish from master/docs](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/)~~

## History
 Also see `/archive/mirror/mirawatt/README.md`
