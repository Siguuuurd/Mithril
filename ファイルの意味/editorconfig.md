# .editorconfig
http://monsat.hatenablog.com/entry/2014/03/04/editorconfig  

## .editorconfig �t�@�C�����L�q
�v���W�F�N�g��root�t�H���_���� .editorconfig ���쐬���A�����ɃR�[�f�B���O�X�^�C�����L�q���܂��傤�B  
�������͂�������Q�Ƃ��Ă�������  
�����Ȃ��͈̂ȉ��̂Ƃ���ł��B  

### root
����́A�v���W�F�N�g�̃��[�g�f�B���N�g���� .editorconfig �������L�q���@�ł��B  
  
```
root = true  
```
  
EditorConfig Plugin�́A�Ȃ�炩�̃t�@�C�����Ђ炢���Ƃ��A�����t�H���_����я�ʊK�w�ɂ��� .editorconfig ��T���܂��B  
���̍� .editorconfig ���Ɉȉ��̋L�q������ƁA����ȏ��ʂ̃t�H���_���������܂���B  

### indent_style, indent_size, tab_width
�C���f���g�̕������w�肵�܂��B

�ȉ��͔��p��2�̗�ł��B
  
```
indent_style = space
indent_size = 2
```
  
indent_style �́A "tab" or "space" ���w��\�ł��B  
tab�̏ꍇ�͈ȉ��̂悤�Ɏw�肵�܂��B tab_width�̏����l��indent_size�̒l�Ƃ̂��Ƃŏȗ��\�̂悤�ł��B  
  
```
indent_style = tab
tab_width = 4
```
  
### end_of_line, charset, insert_final_newline, trim_trailing_whitespace
���s�R�[�h�i"lf" or "cr" or "crlf"�j�A�����R�[�h�A�t�@�C�������̋�s�̗L���A�s���̋󔒂̍폜  
  
```
[*]
end_of_line = lf  
charset = utf-8  
insert_final_newline = true  
trim_trailing_whitespace  = true  
```
  
### ���̑�
�t�@�C���̎�ނɂ��ʂɂ���ꍇ�͉��L�̂悤�ɂȂ�܂��B  
  
```
[*]
indent_style = space
indent_size = 4

[*.html]
indent_style = tab
```