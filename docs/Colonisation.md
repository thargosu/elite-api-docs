
## Colonisation

### ColonisationConstructionDepot

When written: Every 15 seconds while docked at a construction depot

Parameters:

- MarketID
- ConstructionProgress
- ConstructionComplete
- ConstructionFailed
- ResourcesRequired


Example:

```
{
  "timestamp": "2025-04-08T15:51:13Z",
  "event": "ColonisationConstructionDepot",
  "MarketID": 3962369026,
  "ConstructionProgress": 0.328601,
  "ConstructionComplete": false,
  "ConstructionFailed": false,
  "ResourcesRequired": [
    {
      "Name": "$aluminium_name;",
      "Name_Localised": "Aluminio",
      "RequiredAmount": 38454,
      "ProvidedAmount": 29095,
      "Payment": 3239
    },
    {
      "Name": "$ceramiccomposites_name;",
      "Name_Localised": "Compuestos cerámicos",
      "RequiredAmount": 4971,
      "ProvidedAmount": 4971,
      "Payment": 724
    },
    {
      "Name": "$cmmcomposite_name;",
      "Name_Localised": "Compuestos CMM",
      "RequiredAmount": 42999,
      "ProvidedAmount": 338,
      "Payment": 6788
    },
    {
      "Name": "$computercomponents_name;",
      "Name_Localised": "Componentes informáticos",
      "RequiredAmount": 283,
      "ProvidedAmount": 283,
      "Payment": 1112
    },
    {
      "Name": "$copper_name;",
      "Name_Localised": "Cobre",
      "RequiredAmount": 2614,
      "ProvidedAmount": 2614,
      "Payment": 1050
    },
    {
      "Name": "$foodcartridges_name;",
      "Name_Localised": "Cartuchos de alimentos",
      "RequiredAmount": 500,
      "ProvidedAmount": 500,
      "Payment": 673
    },
    {
      "Name": "$fruitandvegetables_name;",
      "Name_Localised": "Frutas y verduras",
      "RequiredAmount": 287,
      "ProvidedAmount": 287,
      "Payment": 865
    },
    {
      "Name": "$insulatingmembrane_name;",
      "Name_Localised": "Membrana aislante",
      "RequiredAmount": 1348,
      "ProvidedAmount": 1348,
      "Payment": 11788
    },
    {
      "Name": "$liquidoxygen_name;",
      "Name_Localised": "Oxígeno líquido",
      "RequiredAmount": 15823,
      "ProvidedAmount": 15823,
      "Payment": 2260
    },
    {
      "Name": "$medicaldiagnosticequipment_name;",
      "Name_Localised": "Equipo de diagnóstico médico",
      "RequiredAmount": 51,
      "ProvidedAmount": 51,
      "Payment": 3609
    },
    {
      "Name": "$nonlethalweapons_name;",
      "Name_Localised": "Armas no letales",
      "RequiredAmount": 49,
      "ProvidedAmount": 49,
      "Payment": 2503
    },
    {
      "Name": "$polymers_name;",
      "Name_Localised": "Polímeros",
      "RequiredAmount": 2023,
      "ProvidedAmount": 2023,
      "Payment": 682
    },
    {
      "Name": "$powergenerators_name;",
      "Name_Localised": "Generadores de energía",
      "RequiredAmount": 130,
      "ProvidedAmount": 130,
      "Payment": 3072
    },
    {
      "Name": "$semiconductors_name;",
      "Name_Localised": "Semiconductores",
      "RequiredAmount": 335,
      "ProvidedAmount": 335,
      "Payment": 1526
    },
    {
      "Name": "$steel_name;",
      "Name_Localised": "Acero",
      "RequiredAmount": 56704,
      "ProvidedAmount": 3,
      "Payment": 5057
    },
    {
      "Name": "$superconductors_name;",
      "Name_Localised": "Superconductores",
      "RequiredAmount": 558,
      "ProvidedAmount": 558,
      "Payment": 7657
    },
    {
      "Name": "$titanium_name;",
      "Name_Localised": "Titanio",
      "RequiredAmount": 33204,
      "ProvidedAmount": 2889,
      "Payment": 5360
    },
    {
      "Name": "$water_name;",
      "Name_Localised": "Agua",
      "RequiredAmount": 6542,
      "ProvidedAmount": 6542,
      "Payment": 662
    },
    {
      "Name": "$waterpurifiers_name;",
      "Name_Localised": "Purificadores de agua",
      "RequiredAmount": 209,
      "ProvidedAmount": 209,
      "Payment": 849
    }
  ]
}
```

### ColonisationContribution

When written: when contributing materials to a colonisation effort

Parameters:

- MarketID
- Contributions


Example:

```
{
  "timestamp": "2025-04-08T15:53:15Z",
  "event": "ColonisationContribution",
  "MarketID": 3962369026,
  "Contributions": [
    {
      "Name": "$Titanium_name;",
      "Name_Localised": "Titanio",
      "Amount": 784
    }
  ]
}
```
