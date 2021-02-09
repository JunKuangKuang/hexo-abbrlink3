# hexo-abbrlink3
A [Hexo plugin](https://hexo.io/plugins/) to generate static post link based on different layouts titles.



This is based on [hexo-abbrlink](https://github.com/rozbo/hexo-abbrlink) secondary development

## How to install

Add plugin to Hexo:

```
npm install hexo-abbrlink3 --save
```

Modify permalink in config.yml file:

```
permalink: :year/:category/:abbrlink/ # Generating effect links
```

There are two settings:

```
alg -- Algorithm (currently support crc16 and crc32, which crc16 is default)
rep -- Represent (the generated link could be presented in hex or dec value)
```

```
# abbrlink config
abbrlink:
  alg: crc16      #support crc16(default) and crc32
  rep: dec        #support dec(default) and hex
  allow: ['post','school','cpp',"java","blog"] #Allowed template types. The default is (" post ")
  disallow: [] #Unallowed template type. Default is an empty list
```

## ThanksFor

[NoahDragon](https://github.com/NoahDragon)

[rozbo](https://github.com/rozbo)

Myself