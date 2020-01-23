unit Unit1;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls;

type
  TForm1 = class(TForm)
    Edit1: TEdit;
    Edit2: TEdit;
    Label1: TLabel;
    Label2: TLabel;
    Button1: TButton;
    procedure Button1Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;

implementation

{$R *.dfm}

procedure TForm1.Button1Click(Sender: TObject);
var satu, dua:real;
begin
edit1.text:=floattostr(strtofloat(edit1.text)+strtofloat(edit2.text)-strtofloat(edit1.text));
edit2.text:=floattostr(strtofloat(edit2.text)/strtofloat(edit1.text));

edit1.text:=floattostr(strtofloat(edit1.text)+strtofloat(edit2.text)-strtofloat(edit1.text));
edit2.text:=floattostr(strtofloat(edit2.text)+strtofloat(edit1.text));

end;

end.
