# HUMANS.md

> Human compatibility standard for agent-native software.

Version: 0.1

## Principle

Build apps for agents. Keep backward compatibility for humans.

## Requirements

A Human Compatible product should let humans:

- Use core functionality without an AI agent
- See when agents perform actions
- Review important actions
- Override or cancel actions where possible
- Access, export, and delete their data

## Levels

- HC0 - Agent only
- HC1 - Human accessible
- HC2 - Human controllable
- HC3 - Full human access, control, history, export, and deletion

## Declaration

    human_compatible:
      version: "0.1"
      level: "HC3"

## Standard

https://humancompatible.dev *(soon)*
