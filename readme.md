

二種組合

- BaseDialogA 跟 DialogA
  - BaseDialoA 沒有對應的 Designer.cs
  - 在 DialogA Designer 中 無法修改 button 的位置
- BaseDialogB 跟 DialogB
  - BaseDialogB 有對應的 Designer.cs
  - DialogB Designer 中 可以修改 button 的位置


> 更改 parent Form 之後，要重新編譯，child Form 才會有變化