# Documentação do Código HTML – Currículo Wanderson Phillype

Este documento detalha a função e o propósito de cada tag HTML presente no código fornecido, com foco em semântica, acessibilidade, SEO e boas práticas de desenvolvimento web.

## 1. Declaração de Documento e Estrutura Básica

<!DOCTYPE html>: Define que o documento é do tipo HTML5
<html lang="pt-BR">: Elemento raiz da página; o atributo lang informa o idioma principal (Português do Brasil), útil para mecanismos de busca e leitores de tela.

## 2. Cabeçalho do Documento (<head>)

<meta charset="UTF-8">: Define o conjunto de caracteres para suporte a acentuação e símbolos especiais.
<meta name="viewport">: Responsividade em dispositivos móveis.
<meta name="description">: Descrição da página, melhora o SEO.
<meta name="keywords">: Palavras-chave para SEO.
<meta name="author">: Informa o autor do site.
<link rel="shortcut icon">: Define o ícone da aba.
<title>: Título da página exibido na aba do navegador.

## 3. Corpo da Página (<body>)

Contém todos os elementos visíveis da página.

## 3.1 Cabeçalho Visual

<header>: Agrupa elementos introdutórios.
<h1>: Título principal.
<img>: Imagem com descrição acessível.
<h2>: Subtítulo.

## 3.2 Seção Sobre

<section>: Bloco de conteúdo com id 'sobre'.
<p>: Parágrafo.
<dl>: Lista de definição para contatos.
<dt> e <dd>: Títulos e descrições.
<a href="tel:"> e <a href="mailto:">: Links clicáveis.
<target="_blank">: Abre em nova aba.
rel="noopener noreferrer": Segurança em links externos.

## 3.3 Formação Acadêmica

<ol>: Lista ordenada.
<li>: Item da lista.
<a>: Link para instituição.
<p>: Informações adicionais.

## 3.4 Experiência Profissional

<table>: Tabela de dados.
<thead>: Cabeçalho da tabela.
<tbody>: Corpo da tabela.
<tr>: Linha.
<th>: Cabeçalho de coluna.
<td>: Dado de célula.

## 3.5 Habilidades

<ul>: Lista não ordenada.
<li>: Habilidade individual.

## 3.6 Endereço com Mapa

<iframe>: Incorpora mapa.
loading="lazy": Carregamento sob demanda.
referrerpolicy: Política de privacidade.
title: Descrição para acessibilidade.

## 3.7 Rodapé

<footer>: Rodapé da página.
<span id="ano-atual">: Espaço reservado para ano.
<script>: JavaScript para atualizar dinamicamente.

## 3.8 Estrutura Geral

<main>: Conteúdo principal.
<section>: Seções lógicas.
<hr>: Separador visual.
