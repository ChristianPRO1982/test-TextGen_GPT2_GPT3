# test-TextGen_GPT2_GPT3

Ce projet a pour objectif de créer une interface permettant de générer des comptes rendus à partir des modèles GPT-2 et GPT-3 de Hugging Face. Il s'agit d'un exercice visant à s'entrainer à développer une interface utilisateur pour l'utilisation de ces modèles de génération de texte.

## Fonctionnalités

- Intégration des modèles GPT-2 et GPT-3 de Hugging Face.
- Interface utilisateur simple pour saisir des demandes de génération de texte.
- Possibilité de choisir entre GPT-2 et GPT-3 pour la génération de texte.
- Génération de comptes rendus basés sur les entrées de l'utilisateur.
- Options de personnalisation pour ajuster les paramètres de génération (longueur du texte, température, etc.).

## Prérequis

- Python 3.8+
- `pip` pour l'installation des dépendances
- Accès à l'API de Hugging Face (pour l'utilisation de GPT-3, vous aurez peut-être besoin d'une clé d'API)

## Installation

1. Clonez ce dépôt :

    ```bash
    git clone https://github.com/votre-utilisateur/test-TextGen_GPT2_GPT3.git
    ```

2. Accédez au répertoire du projet :

    ```bash
    cd test-TextGen_GPT2_GPT3
    ```

3. Installez les dépendances requises :

    ```bash
    pip install -r requirements.txt
    ```

## Utilisation

1. Lancez l'application :

    ```bash
    python main.py
    ```

2. Ouvrez votre navigateur et accédez à l'interface utilisateur.

3. Sélectionnez le modèle (GPT-2 ou GPT-3) et saisissez vos demandes de génération de texte.

4. Cliquez sur le bouton "Générer" pour obtenir le compte rendu.

## Configuration

- Les paramètres de génération de texte tels que la longueur, la température, etc., peuvent être ajustés directement dans l'interface utilisateur.

## Exemple

Voici un exemple simple d'utilisation :

1. Entrez une demande comme "Rédigez un résumé de la réunion de ce matin."
2. Choisissez le modèle (GPT-2 ou GPT-3).
3. Cliquez sur "Générer" pour obtenir le texte généré.

## Contributions

Les contributions sont les bienvenues ! Veuillez suivre les étapes suivantes pour contribuer :

1. Fork ce dépôt
2. Créez une nouvelle branche (`git checkout -b feature-nouvelle-fonctionnalité`)
3. Effectuez vos modifications
4. Poussez la branche (`git push origin feature-nouvelle-fonctionnalité`)
5. Ouvrez une Pull Request

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus d'informations.

## Acknowledgements

- [Hugging Face](https://huggingface.co/) pour les modèles GPT-2 et GPT-3.
- Toute autre ressource ou bibliothèque utilisée dans le projet.

