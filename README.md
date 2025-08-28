# demo-gitlab-projekt

Tento projekt demonstruje GitLab CI/CD pipeline pro deploy na VPS.

## Poznamka -  rozdil mezi gitHUB a gitLAB
GitHub je hlavně platforma pro hostování Git repozitářů a spolupráci na kódu.  
GitLab navíc nabízí integrované CI/CD pipeline, které umožňují automatický deploy a testování přímo z repozitáře.

## Struktura
```
demo-gitlab-projekt/
├── README.md
└── .gitlab-ci.yml
```


- `.gitlab-ci.yml` – ukázková pipeline
- `README.md` – popis projektu

## Jak to funguje

1. Push do repozitáře spustí GitLab CI/CD pipeline.
2. Pipeline může použít SSH klíč (`SSH_PRIVATE_KEY`) pro deploy na vzdálený server.
3. V tomto demo repozitáři je pouze ukázka konfigurace, deploy se reálně nespouští.
4. Pro skutečný deploy je potřeba nastavit proměnné `SSH_PRIVATE_KEY` a `VPS_IP` v GitLab CI/CD.

  


