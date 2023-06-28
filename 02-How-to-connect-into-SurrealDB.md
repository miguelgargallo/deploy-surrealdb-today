<br>
<p align="center">
    <a href="https://surrealdb.com#gh-dark-mode-only" target="_blank">
        <img width="300" src="/img/white/logo.svg" alt="SurrealDB Logo">
    </a>
    <p align="center">
    Guide written by Miguel Gargallo
    </p>
    <h1 align="center">
        How to Connect on SurrealDB
    </h1>
</p>
<br>

## Connect into SurrealDB

```powershell
    surreal sql --conn http://0.0.0.0:8000 --user root --pass A$ecur3Pa$$w0rd --ns type --db form --pretty
```

## If you assigned a domain:
You need to replace to another domain
 - [x] Powershell adapted with fingertip
 - [x] Replace "https://surrealdb.miguelgargallo.com" with your domain.

```powershell
    surreal sql --conn https://surrealdb.miguelgargallo.com --user root --pass A$ecur3Pa$$w0rd --ns type --db form --pretty
```

## If you assigned a decentralized from [Handshake](https://handshake.org) tld or domain with IPFS:
Prerequisites:
 - [x] Powershell adapted with fingertip
 - [x] Replace "https://ultradata" with your tld.

```powershell
    surreal sql --conn https://ultradata --user root --pass A$ecur3Pa$$w0rd --ns type --db form --pretty
```
