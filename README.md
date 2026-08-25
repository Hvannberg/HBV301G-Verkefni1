# 📦 Verkefni #1 - Tegundir krafna og samhengi 

<!-- Fyllið inn í þessa kafla áður en verkefninu er skilað 

Heiti kerfis: 
Höfundar: Nöfn nemenda 
Stutt lýsing á kerfinu
Stutt lýsing á innihaldi geymslunnar. 
    - Lesendur eru viðskiptavinir og kaupendur, notendur, kerfishönnuðir, forritarar og prófarar. Einnig verkefnisstjórar og viðhaldsteymi. 

Annars ráðið þið hvernig þið viljið lýsa geymslunni eða ná til lesenda 
-->

<!-- Nemendur fjarlægi eftirfarandi eftir því sem á við áður en verkefni er skilað 
-->

## Geymslan er í fjórum hlutum
- README, þessi skrá
- SRS - Software Requirement Specifications
- SDS - System Description Specification 
- Vinnuferli 
    - Hópavinna og geymsla
    - Verkaskipting
    - Ígrundun
    - Gagnsæisyfirlýsing um notkun gervigreindar

## Sniðmát fyrir issues 

Undir .gihub/ISSUE_TEMPLATE eru sniðmát til að búa til issues 

## Leiðbeiningar fyrir Template  
Þessi geymsla er sniðmát fyrir námskeiðið HBV301G Verkfræði kröfugreiningar. Notaðu þetta til að:
- Skrá hugbúnaðarkröfur sem Issues
- Skilgreina og skrá SRS skjöl
- Nota GitHub Projects til að fylgjast með stöðu verkefnis. Notið Kanban-borð 

Nemendur: Ýtið á **"Use this template"** til að búa til eigið repo út frá þessum grunni.

Þegar þú kemur inn repo fyrir verkefnið gerirðu: 
- Búðu til Project sem tengist þessu repo og settu það upp með Kanban-borði. 
- Gerðu félaga þinn að collaborator að repo-inu og að project-inu (Settings) 
- Skiptið með ykkur verkum (tasks)

Vinnulagið fyrir verkefnið er eftirfarandi, sem er útskýrt nánar hér á eftir.

**Task/Issue (GitHub) → Create a branch (GitHub) → vinna/commits/push (local) → Pull Request (PR) (GitHub) → review (GitHub) → merge (GitHub) → issue lokast → pull á main (local)**

Eftir merge má eyða vinnubranchinum á GitHub og local. Ef eyddur remote branch sést enn í local má nota git fetch --prune.

Farðu eftir eftirfarandi vinnulagi til að vinna SRS hlutann 
- Búðu til nýtt **Issue**, t.d. "skrá viðskiptakröfur",  fyrir verkið sem á að vinna og úthlutaðu því á annan hvorn teymismeðliminn. Þegar issue-ið er búið til fær það númer, t.d. **#12**.
- Settu issue-ið í réttan dálk á **Kanban-borði** verkefnisins.
- Farðu í issue-ið (**#12**) á GitHub og veldu **Create a branch** undir *Development*.
  Þannig tengist branch-ið sjálfkrafa við issue-ið.
- Vinna skal verkið á branch-inu. Lýstu kröfum í viðeigandi kröfuskrá samkvæmt sniðmáti.
- Þegar þú bætir við  kröfu skaltu bæta henni við **SRS.md** og vísa þar í kröfuna/kröfurnar í kröfuskránni.
- Gerðu **commit og push** reglulega
- Stofnaðu **Pull Request (PR)** á GitHub þegar breytingarnar eru tilbúnar fyrir rýni og skrifaðu `Closes #12` í lýsingu PR svo issue **#12** lokist sjálfkrafa þegar PR-ið er samþykkt og sameinað við `main`
- Teymisfélaginn  rýnir PR-ið. Að rýni lokinni er PR sameinað (merge) við main og issue-inu lokað.  

Ljúktu við aðra þætti verkefnisins eins og SDS og Vinnuferlið með sambærilegum hætti, þ.e. að skipta með ykkur verkum með með issues, branches og PR 
