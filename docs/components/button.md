# Button

## Purpose

Le bouton permet à l’utilisateur de déclencher une action claire et identifiable.

## Notes

Ce composant doit être utilisé de manière cohérente sur toutes les interfaces.

## When to use

Utiliser un bouton lorsqu’une action explicite doit être effectuée par l’utilisateur.

Exemples :

- Enregistrer
- Supprimer
- Créer
- Appliquer
- Télécharger

## When not to use

Ne pas utiliser un bouton pour afficher une simple information ou pour structurer visuellement une page.

## Variants

| Variant | Usage |
|---|---|
| Primary | Action principale et finale de l’écran |
| Secondary | Action importante mais non principale |
| Tertiary | Action complémentaire ou secondaire |
| Small | Action discrète ou contextuelle |

## States

- Default
- Hover
- Focus
- Disabled
- Loading

## Usage rules

- Utiliser un seul bouton Primary par écran.
- Utiliser un label court, clair et orienté action.
- Éviter les labels vagues comme “OK” ou “Valider” si l’action peut être plus précise.
- Si un bouton est disabled, prévoir une raison visible ou accessible.

## Figma

Ajouter ici le lien vers le composant Figma.

## Flutter / Widgetbook

Widget Flutter : `AppButton`

Cas à documenter dans Widgetbook :

- Primary default
- Secondary with icon
- Disabled
- Loading
- Full width mobile

## AI instructions

Use `AppButton` instead of creating a custom Flutter button.

Use Primary only for the main final action of the screen.

Do not use more than one Primary Button on the same screen.

If the button is disabled, provide a visible reason or tooltip.
