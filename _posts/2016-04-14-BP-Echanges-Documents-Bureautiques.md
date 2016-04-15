---
layout: post
title: Les recommandations en matière de diffusion de documents bureautiques dans la sphère étatique
---

# Objectif du document

Ce document a pour objectif de présenter les recommandations de la DINSIC en matière de partage ou de diffusion de documents bureautiques.

# Préambule

Les documents échangés au sein de l’administration et avec l’extérieur s’appuient majoritairement sur des formats intégrés dans des suites bureautiques.

Les suites disponibles sur le marché des logiciels propriétaires et libres acceptent plus ou moins bien les différents formats de documents. Cette situation est susceptible de créer des difficultés dans les échanges.

Depuis la publication du référentiel général d’interopérabilité (RGI) dans sa version 1.0 du 11 novembre 2009, des évolutions de spécifications de format ainsi que leur normalisation par l’ISO sont intervenues et de nombreux logiciels les ont implémentées.

La publication du référentiel général d'interopérabilité dans sa version 2.0 prend acte de ces évolutions et permet désormais de proposer des règles plus précises de mise en œuvre.

# Echange de documents semi-structurés non révisables

La plupart des documents bureautiques échangés ont un but informatif et ne sont pas destinés à être révisés. Il est réellement bénéfique d'échanger des documents dans un format ouvert et parfaitement interopérable.

Pour les échanges de documents bureautiques en mode non révisable, il est OBLIGATOIRE d’utiliser le format PDF (la version normalisée ISO 1.7 est RECOMMANDEE).

Les présentations ne doivent pas embarquer d'animations.

# Echange de documents semi-structurés révisables

Pour les échanges de documents bureautiques semi-structurés en mode révisable, il est RECOMMANDÉ d’utiliser un format de document basé sur le langage XML et dont les spécifications sont normalisées par l'ISO.

II est OBLIGATOIRE d’accepter tout document au format « Open Document Format » (ODF, norme ISO 26300) pour les échanges de documents bureautiques semi-structurés révisables (traitement de texte, tableur, présentation, etc.).

Il est RECOMMANDÉ, dans le cas d’échanges de documents bureautiques semi-structurés révisables de type « feuille de calcul », de privilégier l’utilisation de formules et d’éviter dans la mesure du possible l’usage de « macro ».

Il est OBLIGATOIRE dans le cas d’échanges de documents bureautiques semi-structurés révisables contenant des macros de s’assurer du bon fonctionnement de ces dernières avec les applications de bureautique utilisées par les destinataires.

# Règles de diffusion

La **diffusion** de documents **en vue d'un partage** collaboratif ou de modifications de la part des utilisateurs doit se faire, dans la mesure des possibilités offertes par les logiciels de l’émetteur, dans les **formats ODF v1.2**.

Pour diffuser un document de type texte, le format recommandé est ODT.

Pour diffuser un document de type feuille de calcul, le format recommandé est ODS.

Pour diffuser un document de type présentation, le format recommandé est ODP.

Les versions 2007 et 2010 de Microsoft Office produisent des fichiers au format ODF 1.1 qui ne sont pas toujours conformes avec LibreOffice. Pour résoudre ces difficultés, on peut compléter l’envoi avec le format PDF.

Dans le cas où le logiciel utilisé par l'agent ne permet pas la génération de fichier au format ODF v1.2, la possibilité de diffuser un document au format DOCX ou XLSX ou PPTX est laissé à l'utilisateur.

L'usage des formats DOCX ou PPTX dans la diffusion de documents en vue d'une modification n'est pas recommandé, le format XLSX peut être utilisé dans le cas où les feuilles de calcul contenues dans le fichier activent des macros indispensables au bon fonctionnement du tableau.

## Matrice des formats à utiliser en fonction de l'usage et des logiciels à disposition de l'émetteur

<table cellpadding="5" cellspacing="2" border="2">
  <caption>Matrice des formats des documents bureautiques</caption>
  <tr>
    <th>Type de suite utilisée</th>
    <th>document texte</th>
    <th>Présentation (sans animation)</th>
    <th>Feuille de calcul (sans macro)</th>
    <th>Feuille de calcul (avec macro)</th>
  </tr>
  <tr>
    <td>Microsoft Office < = 2003 (déconseillé)</td>
    <td>PDF</td>
    <td>PPT+PDF</td>
    <td>XLS</td>
    <td>XLS</td>
  </tr>
  <tr>
    <td>Microsoft Office 2007 ou 2010</td>
    <td>ODT+PDF</td>
    <td>ODP+PDF</td>
    <td>ODS+XLS</td>
    <td>XLS</td>
  </tr>
  <tr>
    <td>Microsoft Office > = 2013</td>
    <td>ODT</td>
    <td>ODP</td>
    <td>ODS</td>
    <td>ODS+XLSX</td>
  </tr>
  <tr>
    <td>OpenOffice ou LibreOffice > = 3</td>
    <td>ODT</td>
    <td>ODP</td>
    <td>ODS</td>
    <td>ODS</td>
  </tr>
</table>


## OOXML : Extrait du RGI v2.0

Office Open XML est une norme ISO/CEI 29500 créée par Microsoft, destinée à répondre à la
demande d’interopérabilité dans les environnements de bureautique. Ce format (dont les suffixes
sont .docx, .xlsx, .pptx...) est utilisé à partir de Microsoft Office 2007, en remplacement des
précédents formats Microsoft (reconnus à leurs suffixes tels que : .doc, .xls, .ppt), il est toutefois
légèrement différent, pour ces versions d'office, de la norme ISO définitive, qui a tenu compte
des remarques des membres de l'organisme normalisateur. Seule la suite Office à partir de la
version 2013 est totalement compatible avec la norme (en lecture et en écriture).

Le standard OOXML est conservé dans le RGI au statut « en observation ». Sa complexité, son manque
d’ouverture (notamment dans la gouvernance de la norme) et le strict respect tardif de la norme
par Microsoft même n’ont pas permis de réviser son statut. La version « transitionnal » de la norme n’est quant à elle pas recommandée. Pour des besoins   d’échanges   d’informations   sous   forme   de   tableaux   qui   notamment embarquerait du code, l’utilisation d’OOXML peut être une alternative. C’est toutefois une pratique à encadrer.
