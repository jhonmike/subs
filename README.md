## subs


This project aims to reduce the amount of things we type.

We are used to messy languages and they could be improved.

## Examples:


```
<?php


cl person
	pf isBad

cl dog
  co color
  pf bark people
  fe people person
    if person->isbad()
      $this->bark()
  pf bite person

cl dog
  co color
  pf bite person
  pf bark people
    fe people person
      if person->isbad()
        $this->bark()

```

