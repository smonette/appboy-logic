# Appboy Logic
A place to store all the logic and filters that come in handy


### Computing potential savings 
$`{{ distance | times: 0.535  | round: 2 }}`


### Adding 7 days to current date 
`{{'now' | date: "%s" | plus : 604800 | date: "%b %d, %Y"}`


### Test which country
`{% if {{${country}}} == 'GB' %}`

`{% if {{${country}}} == 'US' %}`

`{% if {{${country}}} == 'CA' %}`


### Print user's name, or defualt
Hello `{{custom_attribute.${Username} | default: 'there'}}`


### Test which Unit of measurement
`{% if {{custom_attribute.${Use Metric}}} == false %}`

`{% if {{custom_attribute.${Use Metric}}} == true %}`


### Other Goodies
`{{${user_id}}}`

`{{event_properties.${Distance}}}`

`{{event_properties.${Potential Value}}}`

`{{event_properties.${MTD Unclassified Value}}}`

`{{event_properties.${MTD Business Value}}}`

`{{event_properties.${MTD Drives}}`
