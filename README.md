# firebase-boilerplate

A template for creating new google firebase projects

## Getting Started

### Setting up Firebase Project

1. Clone repo

2. Install dependencies

```
npm install
```

3. Login to firebase

```
firebase login
```

4. Initialise firebase project

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