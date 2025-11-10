# Titan armor filter  
```
(exactperk:paragon and tertiarystat:grenade) or (exactperk:paragon and tertiarystat:class) or (exactperk:paragon and tertiarystat:weapons) or (exactperk:gunner and tertiarystat:melee) or (exactperk:gunner and tertiarystat:super) or (exactperk:gunner and tertiarystat:class) basestat:total:75 is:titan
```
```
basestat:total:75 is:titan  -notes:#paragon
```

```
basestat:total:75 is:titan -is:iningameloadout -is:indimloadout -notes:#paragon
```

```
basestat:total:75 is:titan is:iningameloadout is:indimloadout tag:junk
```
```
basestat:total:75 is:titan is:iningameloadout is:indimloadout tag:infuse
```

# Query what to delete so we can tag it for delete  
```
is:legendary is:titan -is:iningameloadout -is:indimloadout -notes:#paragon -notes:#gunner
```
or
```
is:legendary is:titan -is:iningameloadout -is:indimloadout -notes:#minor
```

# Gunner Titan Filter  
```
(exactperk:gunner and tertiarystat:melee) or (exactperk:gunner and tertiarystat:super) or (exactperk:gunner and tertiarystat:class) basestat:total:75 is:titan -is:locked
```

## Set notes to:  
```
#gunner #minor:class,melee,grenade
```

# Paragon Titan filter  
```
(exactperk:paragon and tertiarystat:grenade) or (exactperk:paragon and tertiarystat:class) or (exactperk:paragon and tertiarystat:weapons) basestat:total:75 is:titan -is:locked
```

## Set notes to:  
```
#paragon #minor:class,melee,grenade
```
