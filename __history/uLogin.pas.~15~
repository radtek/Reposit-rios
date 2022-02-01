unit uLogin;

interface

uses
  System.SysUtils, System.Types, System.UITypes, System.Classes, System.Variants,
  FMX.Types, FMX.Controls, FMX.Forms, FMX.Graphics, FMX.Dialogs, FMX.Objects,
  FMX.Layouts, FMX.Controls.Presentation, FMX.Edit, FMX.StdCtrls, FMX.TabControl,
  System.Actions, FMX.ActnList;

type
  TfrmLogin = class(TForm)
    Layout2: TLayout;
    imgLoginLogo: TImage;
    Layout1: TLayout;
    RoundRect1: TRoundRect;
    edtLoginEmail: TEdit;
    StyleBook1: TStyleBook;
    Layout3: TLayout;
    RoundRect2: TRoundRect;
    edtLoginSenha: TEdit;
    Layout4: TLayout;
    RoundRect3: TRoundRect;
    Label1: TLabel;
    TabControl1: TTabControl;
    tbLogin: TTabItem;
    tbConta: TTabItem;
    Layout5: TLayout;
    Image1: TImage;
    Layout6: TLayout;
    RoundRect4: TRoundRect;
    edtContaNome: TEdit;
    Layout7: TLayout;
    RoundRect5: TRoundRect;
    edtContaSenha: TEdit;
    Layout8: TLayout;
    rctProximo: TRoundRect;
    lblProximo: TLabel;
    Layout9: TLayout;
    RoundRect7: TRoundRect;
    edtContaEmail: TEdit;
    tbFoto: TTabItem;
    Layout10: TLayout;
    crcFoto: TCircle;
    Layout11: TLayout;
    rctCriaConta: TRoundRect;
    Label3: TLabel;
    tbEscolha: TTabItem;
    Layout12: TLayout;
    Label4: TLabel;
    imgCamera: TImage;
    imgGaleria: TImage;
    Layout13: TLayout;
    imgVoltarConta: TImage;
    Layout14: TLayout;
    imgVoltarEscolha: TImage;
    Layout15: TLayout;
    Layout16: TLayout;
    lblLogin: TLabel;
    lblCriaConta: TLabel;
    Rectangle1: TRectangle;
    ActionList1: TActionList;
    actConta: TChangeTabAction;
    actEscolha: TChangeTabAction;
    actFoto: TChangeTabAction;
    actLogin: TChangeTabAction;
    Layout17: TLayout;
    Layout18: TLayout;
    lblContaLogin: TLabel;
    Label6: TLabel;
    Rectangle4: TRectangle;
    procedure lblCriaContaClick(Sender: TObject);
    procedure lblContaLoginClick(Sender: TObject);
    procedure rctProximoClick(Sender: TObject);
    procedure imgVoltarContaClick(Sender: TObject);
    procedure crcFotoClick(Sender: TObject);
    procedure imgVoltarEscolhaClick(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  frmLogin: TfrmLogin;

implementation

{$R *.fmx}

procedure TfrmLogin.crcFotoClick(Sender: TObject);
begin
  actEscolha.Execute;
end;

procedure TfrmLogin.imgVoltarContaClick(Sender: TObject);
begin
  actConta.Execute;
end;

procedure TfrmLogin.imgVoltarEscolhaClick(Sender: TObject);
begin
  actFoto.Execute;
end;

procedure TfrmLogin.lblContaLoginClick(Sender: TObject);
begin
  actLogin.Execute;
end;

procedure TfrmLogin.lblCriaContaClick(Sender: TObject);
begin
  actConta.Execute;
end;

procedure TfrmLogin.rctProximoClick(Sender: TObject);
begin
  actFoto.Execute;
end;

end.
