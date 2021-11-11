---
title: Palaikymo ciklo duomenų eksportavimo instrukcijos
description: Produkto gyvavimo ciklo informacijos eksportavimo instrukcijos
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546864"
---
# <a name="lifecycle-data-export-guidance"></a>Palaikymo ciklo duomenų eksportavimo instrukcijos
Šiame dokumente aprašoma, kaip naudoti produkto eksportavimo failą.

## <a name="query-information"></a>Užklausos informacija
„Excel“ dokumente yra laukų, kurie padės nustatyti produktų lentelėje automatiškai įvestus duomenis.

### <a name="end-of-support"></a>Palaikymo pabaiga
Pateikus palaikymo pabaigos vertę produktai filtruojami arba pagal produkto palaikymo pabaigos datą, arba jo išleidimo pabaigos datas.

Galimos vertės: Viskas (netaikomas joks filtras), Metai ir Diapazonas.

### <a name="family"></a>Šeima
Naudojant šeimos vertę produktai filtruojami pagal pirminį hierarchijos lygį, vadinamą šeima.

Galimos vertės: Viskas (netaikomas joks filtras), Šeimos vardas

### <a name="group"></a>Grupė
Naudojant grupės vertę produktai filtruojami pirminiu lygiu (šeimos) į konkrečią grupę.

Galimos vertės: Viskas (netaikomas joks filtras), Grupės pavadinimas

## <a name="table-columns"></a>Lentelės stulpeliai
Produkto lentelę sudaro stulpeliai, kuriuose apibrėžiamas produktas, leidimai, išleidimas ir atitinkamos palaikymo datos.

> [!NOTE]
> Yra kiekvienam produktui, leidimui ir išleidimo deriniui skirta eilutė.

### <a name="product"></a>Produktas
Produkto pavadinimas.

### <a name="edition"></a>Leidimas
Leidimo stulpelis automatiškai užpildomas, kai produkte yra leidimų. Kai produkto leidimo nėra, šis laukas bus tuščias.

### <a name="release"></a>Pateikimas
Išleidimo stulpelis bus automatiškai užpildomas, kai produkte yra keli išleidimai.
Kai produktas išleidžiamas tik vieną kartą, šis laukas bus tuščias.

### <a name="support-policy"></a>Palaikymo strategija
Šiame lauke apibrėžiama, kuri palaikymo strategija taikoma produktui.

Galimos vertės: [Fiksuotoji](/lifecycle/policies/fixed), [Modernioji](/lifecycle/policies/modern), Komponento

### <a name="start-date"></a>Pradžios data
Produkto palaikymo pradžios data.

### <a name="mainstream-date"></a>Pagrindinė data
Kai palaikymo strategija **yra Fiksuotoji** **arba** Komponento, tai yra produkto pagrindinė pabaigos datos data.
  
Kai palaikymo strategija yra **Modernioji**, šis laukas bus tuščias.

### <a name="extended-end-date"></a>Papildomo palaikymo pabaigos data
Kai palaikymo strategija yra **Fiksuotoji** arba **Komponento**, tai yra data, kai baigėsi produkto papildomo palaikymo laikotarpis.

Kai palaikymo strategija yra **Modernioji**, šis laukas bus tuščias.

### <a name="retirement-date"></a>Užbaigimo data
Kai palaikymo strategija yra **Fiksuotoji** arba **Komponento**, šis laukas bus tuščias.

Kai palaikymo strategija yra **Modernioji**, tai bus produkto naudojimo užbaigimo data.

### <a name="release-start-date"></a>Išleidimo pradžios data
Data, kada prasidėjo išleidimo palaikymo laikotarpis. Kai produktas išleidžiamas tik vieną kartą, šis laukas bus tuščias.
 
### <a name="release-end-date"></a>Išleidimo pabaigos data
Data, kai baigėsi išleidimo palaikymo laikotarpis.
Kai produktas išleidžiamas tik vieną kartą, šis laukas bus tuščias.

### <a name="docs-url"></a>Dokumentų URL
Išplėstinės dokumentacijos URL.
