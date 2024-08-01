# Lazarus
Sistema de alimentacion de ganado para integracion en salas de ordeño en proceso de automatizacion.

## Índice

1. [Introducción](#1-introducción)
    - [Descripción del Proyecto](#11-descripción-del-proyecto)
    - [Objetivos](#12-objetivos)
    - [Alcance](#13-alcance)
2. [Requisitos del Sistema](#2-requisitos-del-sistema)
    - [Requisitos de Hardware](#21-requisitos-de-hardware)
    - [Requisitos de Software](#22-requisitos-de-software)
    - [Especificaciones Técnicas](#23-especificaciones-técnicas)
3. [Diseño del Sistema](#3-diseño-del-sistema)
    - [Arquitectura del Sistema](#31-arquitectura-del-sistema)
    - [Diagramas de Componentes](#32-diagramas-de-componentes)
        - [Diagrama Esquemático General](#321-diagrama-esquemático-general)
        - [Conexiones de Hardware](#322-conexiones-de-hardware)
4. [Configuración del Hardware](#4-configuración-del-hardware)
    - [Raspberry Pi Zero 2W](#41-raspberry-pi-zero-2w)
        - [Configuración Inicial](#411-configuración-inicial)
        - [Conexiones I2C](#412-conexiones-i2c)
    - [ATmega 328](#42-atmega-328)
        - [Pantalla 16x2](#421-pantalla-16x2)
        - [Teclado 4x4](#422-teclado-4x4)
        - [Actuador](#423-actuador)
        - [Sensor de Inducción](#424-sensor-de-inducción)
        - [Botón de Parada de Emergencia](#425-botón-de-parada-de-emergencia)
5. [Desarrollo del Software](#5-desarrollo-del-software)
    - [Configuración del Entorno de Desarrollo](#51-configuración-del-entorno-de-desarrollo)
        - [Instalación de Herramientas en Ubuntu](#511-instalación-de-herramientas-en-ubuntu)
    - [Programación de la Raspberry Pi](#52-programación-de-la-raspberry-pi)
        - [Comunicación I2C con ATmega 328](#521-comunicación-i2c-con-atmega-328)
    - [Programación del ATmega 328](#53-programación-del-atmega-328)
        - [Código del Maestro (Raspberry Pi)](#531-código-del-maestro-raspberry-pi)
        - [Código de los Esclavos (ATmega 328)](#532-código-de-los-esclavos-atmega-328)
            - [Pantalla 16x2](#5321-pantalla-16x2)
            - [Teclado 4x4](#5322-teclado-4x4)
            - [Actuador](#5323-actuador)
            - [Sensor de Inducción](#5324-sensor-de-inducción)
            - [Botón de Parada de Emergencia](#5325-botón-de-parada-de-emergencia)
6. [Integración y Pruebas](#6-integración-y-pruebas)
    - [Integración del Sistema](#61-integración-del-sistema)
    - [Pruebas de Hardware](#62-pruebas-de-hardware)
    - [Pruebas de Software](#63-pruebas-de-software)
    - [Validación del Sistema](#64-validación-del-sistema)
7. [Implementación](#7-implementación)
    - [Despliegue del Sistema](#71-despliegue-del-sistema)
    - [Documentación del Usuario](#72-documentación-del-usuario)
        - [Manual del Usuario](#721-manual-del-usuario)
        - [Solución de Problemas Comunes](#722-solución-de-problemas-comunes)
8. [Mantenimiento](#8-mantenimiento)
    - [Plan de Mantenimiento](#81-plan-de-mantenimiento)
    - [Actualizaciones de Software](#82-actualizaciones-de-software)
9. [Anexos](#9-anexos)
    - [Esquemas Detallados](#91-esquemas-detallados)
    - [Códigos Fuente](#92-códigos-fuente)
    - [Referencias](#93-referencias)

## 1. Introducción
Lazarus es un proyecto de desarroyo de hardware para laimplementacion de un sistema de alimentacion de ganado. 
En este repositorio se presenta su primera construccion de softare versionado. 

### 1.1. Descripción del Proyecto
### 1.2. Objetivos
### 1.3. Alcance

## 2. Requisitos del Sistema
### 2.1. Requisitos de Hardware
### 2.2. Requisitos de Software
### 2.3. Especificaciones Técnicas

## 3. Diseño del Sistema
### 3.1. Arquitectura del Sistema
### 3.2. Diagramas de Componentes
#### 3.2.1. Diagrama Esquemático General
La representacion esquematica del hardware de este proyecto se ve en la siguiente imagen:
![Esquematico de hardware](esquematico.png)
#### 3.2.2. Conexiones de Hardware

## 4. Configuración del Hardware
### 4.1. Raspberry Pi Zero 2W
#### 4.1.1. Configuración Inicial
#### 4.1.2. Conexiones I2C
### 4.2. ATmega 328
#### 4.2.1. Pantalla 16x2
#### 4.2.2. Teclado 4x4
#### 4.2.3. Actuador
#### 4.2.4. Sensor de Inducción
#### 4.2.5. Botón de Parada de Emergencia

## 5. Desarrollo del Software
### 5.1. Configuración del Entorno de Desarrollo
#### 5.1.1. Instalación de Herramientas en Ubuntu
### 5.2. Programación de la Raspberry Pi
#### 5.2.1. Comunicación I2C con ATmega 328
### 5.3. Programación del ATmega 328
#### 5.3.1. Código del Maestro (Raspberry Pi)
#### 5.3.2. Código de los Esclavos (ATmega 328)
##### 5.3.2.1. Pantalla 16x2
##### 5.3.2.2. Teclado 4x4
##### 5.3.2.3. Actuador
##### 5.3.2.4. Sensor de Inducción
##### 5.3.2.5. Botón de Parada de Emergencia

## 6. Integración y Pruebas
### 6.1. Integración del Sistema
### 6.2. Pruebas de Hardware
### 6.3. Pruebas de Software
### 6.4. Validación del Sistema

## 7. Implementación
### 7.1. Despliegue del Sistema
### 7.2. Documentación del Usuario
#### 7.2.1. Manual del Usuario
#### 7.2.2. Solución de Problemas Comunes

## 8. Mantenimiento
### 8.1. Plan de Mantenimiento
### 8.2. Actualizaciones de Software

## 9. Anexos
### 9.1. Esquemas Detallados
### 9.2. Códigos Fuente
### 9.3. Referencias