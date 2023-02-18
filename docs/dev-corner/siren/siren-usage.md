---
title: Uso di Siren
description: Dovrai inizializzare Siren prima di poter usare quello che ha da offrirti.
---

### Uso di Siren

Dovrai inizializzare Siren prima di poter usare quello che ha da offrirti. 

Potrai farlo richiamando il metodo `Initialize`

Raccomandiamo l'uso dentro al tuo costruttore del plugin che stai scrivendo.

Ricordati inoltre di usare il dispose di Siren quando il tuo plugin non viene caricato.

 Puoi farlo richiamando il metodo `Dispose`. Raccomandiamo l'uso dentro al metodo dispose del tuo plugin.
 
### Esempio d'uso

```csharp
using Siren;

public class MioPlugin : IDalamudPlugin
{
    public string Name => "MioPlugin";

    public MioPlugin(DalamudPluginInterface pluginInterface)
    {
        SirenCore.Initialize(pluginInterface, Name);
    }

    public void Dispose()
    {
        Siren.Dispose();
    }
}
```