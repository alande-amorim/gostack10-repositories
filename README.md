# Listing GitHub Repos
This project was developed by studying and following [RocketSeat](https://rocketseat.com.br/)'s GoStack10 bootcamp lessons.

## Sumary
This ReactJS app covers how to integrate with GitHub API in order to display a list of repositories.
The app stores the name of the repository provided by the user inside LocalStorage, retrieves the data from the GitHub API and updates the interface.
By clicking on an item in the list, the user is sent to a page where detailed info for the repo he chose  is then displayied. The reference of the chosen repo is passed as a URL parameter through navigation, the app later calls the GitHub API again to obtain the detailed data and its issues.


## Techs
- NodeJS
- Yarn
- Webpack
- Babel
- React
- Axios
- PropTypes
- Styled Components
- ESlint

## Installing and using

```bash
$ git clone https://github.com/alande-amorim/gostack10-repositories.git
$ cd gostack10-repositories/
$ yarn install
$ yarn start
```

