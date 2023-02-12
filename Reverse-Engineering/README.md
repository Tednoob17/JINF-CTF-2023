# JINF-CTF-2023 👨‍💻️

### Kira's_team 👨‍👨‍👦‍👦️
1. Kira `Captain` 👨‍✈️️
2. amo_weak 🕵️
3. Eddy 👨‍🔬️
4. Hyd3 🧙️

## Author: Hyd3 From Kira's_team

## Reverse Engineering Challenges
________________________________________________________
|Challenge		|Category	    	|Value  |
| ---------------------	|  ------------------	| ----- |
|[x] La devinette       | Reverse Engineering	|  100  |
|[x] Crack me		| Reverse Engineering	|  200  |
---------------------------------------------------------

	- La devinette
		- Premiere méthode
		- Seconde  méthode
	- Crack me
		- Premiere méthode
		- Seconde  méthode
		
#### Let's Go🏇️

## 1. La devinette

**Download** [pass](../Files/pass "pass") (Binary file)

1. Premiere méthode

>Tout d'abord pour savoir a quoi on doit s'attendre

```bash
file pass
```

`Output`


![pass](../Images/filepass.png)

Le binaire n'est pas strippé Dieu merci
>On ne s'agite pas on ne sait amais ce qui peut se passer avec un binaire , on pourrait avoir des informations utiles dans les 
`strings`


```bash
strings pass
```

![pass](../Images/header.png)

Lâ on peut voir toutes les sections contenues dans le binaire

En Faisant des recherche vous verez que la section `.rodata` contient les données qui peuvent etre en clair dans le binaire 




































































