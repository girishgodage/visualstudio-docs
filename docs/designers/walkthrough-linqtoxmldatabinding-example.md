---
title: "Walkthrough: LinqToXmlDataBinding Example"
ms.date: 11/04/2016
ms.topic: conceptual
ms.assetid: aedf42e8-896c-48fa-88df-7f7c9536aa69
author: jillre
ms.author: jillfra
manager: jillfra
ms.workload:
  - "multiple"
---
# Walkthrough: LinqToXmlDataBinding example
This walkthrough describes the LinqToXmlDataBinding example, and explains some of the more interesting contents of its two primary source files, *L2DBForm.xaml* and *L2DBForm.xaml.cs*.

## Prerequisites
Before you read this walkthrough, we highly recommended that you build and run the LinqToXmlDataBinding program as described in [How to: Build and run the LinqToXmlDataBinding example](../designers/how-to-build-and-run-the-linqtoxmldatabinding-example.md).

## Remarks
 The LinqToXmlDataBinding program is a Windows Presentation Foundation (WPF) application that is composed of C# and XAML source files. It contains an embedded XML document that defines a list of books, and enables the user to view, add, delete, and edit these entries. It is composed of the following two primary source files:

- *L2DBForm.xaml* contains the XAML declaration code for the user interface (UI) of the main window. It also contains a window resource section that defines a data provider and embedded XML document for the book listings.

- *L2DBForm.xaml.cs* contains the initialization and event-handling methods associated with the UI.

  The main window is divided into the following four vertical UI sections:

- **XML** displays the raw XML source of the embedded book listing.

- **Book List** displays the book entries as standard text and enables the user to select and delete individual entries.

- **Edit Selected Book** enables the user to edit the values associated with the currently selected book entry.

- **Add New Book** enables the creation of a new book entry based on values entered by the user.

## In this section

|Topic|Description|
|-----------|-----------------|
|[L2DBForm.xaml source code](../designers/l2dbform-xaml-source-code.md)|Contains the contents and description of the XAML code in file L2DBForm.xaml.|
|[L2DBForm.xaml.cs source code](../designers/l2dbform-xaml-cs-source-code.md)|Contains the contents and description of the C# source code in the file L2DBForm.xaml.cs.|

## See also

- [WPF data binding using LINQ to XML example](../designers/wpf-data-binding-using-linq-to-xml-example.md)
- [How to: Build and run the LinqToXmlDataBinding example](../designers/how-to-build-and-run-the-linqtoxmldatabinding-example.md)