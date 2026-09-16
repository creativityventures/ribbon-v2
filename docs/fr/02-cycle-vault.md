# Cycle d’un vault

Un round de vault suit des étapes : accepter les dépôts, verrouiller les fonds, sélectionner le strike, vendre l’option, attendre l’échéance puis régler. Les états et timestamps empêchent de mélanger deux rounds.

Les parts représentent la créance sur la valeur du vault ; les calculs de share price et les retraits doivent tenir compte des actifs immobilisés et des primes reçues.

Suite : [pricing et settlement](./03-pricing-settlement.md).
