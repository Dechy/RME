# RME : RPG Maker Extender
Outil d'extension de RPG Maker (les objets étendus ne sont documentés que pour les ajouts.)

[Documentation](README.md) > [Classes et modules](Classes%20et%20modules.md) > **Generative::CommandAPI**  
- - -  
# Generative::CommandAPI
Rend accessibles les commandes EventExtender

## Liste des méthodes
*    [self.command(name, args)](#selfcommandname-args)


## Description des méthodes
##### self.command(name, args)

> Appel d'une commande, alias : c, cmd

  
Nom|Type|Description  
--- | --- | ---  
`name`|`Symbol`|Nom de la commande à appeler  
`args`|`Argslist`|Suite d'arguments  


Exemple  
```ruby  
command(:test, 1, 2, 3) #Appel Command.test(1,2,3) (ou : c(:test, 1,2,3) ou cmd(:test, 1,2,3)  
```



