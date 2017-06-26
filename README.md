# Appboy Logic
A place to store all the logic and filters that come in handy


### Computing potential savings 
$`{{ distance | times: 0.535  | round: 2 }}`


### Adding 7 days to current date 
`{{'now' | date: "%s" | plus : 604800 | date: "%b %d, %Y"}`
