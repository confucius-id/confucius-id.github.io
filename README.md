# ConfuciusID

**Education for all**

> _If you can one day renovate yourself, do so from day to day._
> _Yea, let there be daily renovation.._
> _~Da Xue III:4_

## Configuration
1. Environments

| environment | description | example |
|--|--|--|
| VITE_PORT | vite development port | 551 |
| VITE_PREVIEW_PORT | vite preview port (used for `npm run preview`) | 479 |
| VITE_PUBLIC_URL | application url without end slashes | https://confucius.github.io |
| VITE_API_HOST | api host url without end slashes | https://confucius.github.io |
| VITE_GOOGLE_ANALYTICS_ID | google analytic/tag manager id | GA-23XYZ |

## Development
### Starting the app
1. Install the dependencies: `npm install` (as needed)
2. Setup the environment config: `cp .env.example .env`
3. Run the app: `npm start`
4. Check on: `localhost:551`

## Deployment
### Setup
1. Install the dependencies: `npm install` (as needed)
2. Setup the environment config: `cp .env.example .env`
3. Build the app: 
- `npm run deploy:dev` (dev deployment)
- `npm run deploy:prod` (prod deployment)
4. Setup the server to host the build folder:
- `/build` (original build)
- `/snap-build` (prerender build)

## Todos
1. Multilingual page detail view
2. Preview page (book, music, etc)
3. Enhance music filter (multiple firstChar, removeable firstChar)
4. Add book: Shijing
5. Add book: Shujing
6. Add book: Yijing
7. Add book: Lijing
8. Add book: Chunqiujing
9. Add prayer letter
10. Add media -> hyperlink to medium

## Nice to Have
Nothing to have right now

## Issues
No issues right now

## References:
1. [MATAKIN](https://matakin.or.id/)
2. [Chinese Text](https://ctext.org/)
3. [Wengu zhixin](http://wengu.tartarie.com/wg/wengu.php)
