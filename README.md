# Django Food - AAHI goes open source.
Open source backend for food ordering cross-platform applications built on Django framework.

This project is an effort to open-source the food-ordering platform [AAHI by Apex Labs](https://aahi.io) 
which is currently in production.

## Progress

We are currently working on open-sourcing the platform which requires removing business specifics from the code and some
refactoring. Please keep coming back to follow the progress, feel free to open an issue or ask a question.


## What is included?

```
├── LICENSE
|
├── README.md
|
└── src
    ├── core - Core functionality and data models, like currencies, countries and other platform-wide utilities
    |
    ├── inventory - Products and dishes, i.e. restaurant menu
    |
    ├── sales - Orders, taxes, invoices, integrations etc
    |
    ├── stores - Business details, shops, openining times, addresses, brands
    |
    ├── cloudprint - Receipt printing from the cloud
    |
    ├── delivery - Tracking orders delivery
    |
    ├── links - Cross-platoform deep-linking via QR codes and NFT chips (QR ordering)
    |
    ├── notifications - Push notifications, text messages, automated phone calls, e-mail
    |
    └── users - Authentication and customer profiles
```


Copyright (c) 2018-2021, AAHI by ApexLabs, https://aahi.io
