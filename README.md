# demo-gitlab-projekt

Tento projekt demonstruje GitLab CI/CD pipeline pro deploy na VPS.

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

