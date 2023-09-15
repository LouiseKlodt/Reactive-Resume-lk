<img src="/client/public/logo/dark.svg" alt="Reactive Resume" width="256px" height="256px" />

# Reactive Resume

# Local Build

## Prerequisites
1. install `npm` and `postgres`
2. Connect to postgres and create `postgres` user:
 ```bash
~ psql postgres

postgres=# CREATE USER postgres;
postgres=# ALTER DATABASE postgres OWNER TO postgres;
```
3. Follow the steps at https://docs.rxresu.me/source-code/local-build
4. Add values for `SECRET_KEY` and `JWT_SECRET` in your `.env` file

5. Build and start server:
```bash
pnpm build
pnpm start
```
6. Navigate to http://localhost:3000/





## License

Reactive Resume is packaged and distributed using the [MIT License](https://choosealicense.com/licenses/mit/) which allows for commercial use, distribution, modification and private use provided that all copies of the software contain the same license and copyright.

_By the community, for the community._
A passion project by [Amruth Pillai](https://amruthpillai.com/)
