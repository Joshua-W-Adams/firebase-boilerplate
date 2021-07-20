# firebase-boilerplate

A template for creating new google firebase projects

## Getting Started

### Create new Project

1. Clone repo

2. Initialise project with command line tool or other. E.g.

    Create a react application using Facebooks starter boilerplate

    ```
    npx create-react-app --template typescript
    ```

    OR Create Flutter application

    ```
    flutter create my_app
    ```

### Setting up Firebase Project

Note: Firebase project should be setup after configuring the initial project to avoid conflicts project starter tools like npx create-react-app.

1. Login to firebase

```
firebase login
```

2. Initialise firebase project

```
firebase init
```

### Setting up CI/CD with GitHub Actions

1. Get firebase token

```
firebase login:ci
```

2. Add FIREBASE_TOKEN to git repository 

```
Github repo setting -> Secrets
```

3. Automatic deployments will now occur on commits to master branch