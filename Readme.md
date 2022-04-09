# Intro

This is a simple project to use along with a dotnet web api deployment tutorial.

# Commands

## Dev

```shell
cd dotnetwebapi
dotnet run
```

## Create a publish folder

Note: you can also use UI to create the folder.
Please don't use the single file approach, we need the dll to make this work.

```shell
dotnet publish --configuration Release -o published
```

## Run the publish

```shell
cd <publish-folder>
dotnet app-name.dll
```
