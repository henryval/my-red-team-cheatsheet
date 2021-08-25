## my-red-team-cheatsheet

Tools to help in red team assesments

## Subdomain enumeration

### theHarvester

Get emails, hosts, ips, subdomains and more information from your target using [theHarvester](https://github.com/laramies/theHarvester)

```python3 theHarvester.py -d example.com -b all```

### sublist3r

Enumerate subdomains via several sources using [sublist3r](https://github.com/aboul3la/Sublist3r)

```sublist3r -d example.com```

### subbrute

Enumerate subdomains by brute forcing prefixes into the base subdomain [subbrute](https://github.com/TheRook/subbrute)

```subbrute /path/wordlist.txt example.com```


### xxx

Tool []()

``` ```



## Username enumeration




## Mail checklist


## BloodHound Custom Query

Bloodhound query to mark multiple users as owned.

```MATCH (m:User) WHERE m.name =~ '.*(USER_1|USER_2|USER_3|USER_4|USER_ALWAYS_IN_CAPITAL).*' SET m.owned=TRUE```

If you need machines just change m:Computer.

