# NOTIFICAÇÃO
Include para fazer que não tenha muitas mensagens no chat e para substituir os SCM com ou sem format.

## MODO DE USO

```pawn

#define ICONE_ERRO 			"hud:thumbdn"
#define ICONE_AVISO 		"hud:badchat"
#define ICONE_CERTO 		"hud:thumbup"

notificacao(playerid, titulo, mensagem, sprite);

notificacao(playerid, "AVISO", "Você foi avisado", ICONE_AVISO);

format(Str, sizeof(Str), "O %s mostrou uma notificao para você", Name(playerid));
notificacao(playerid, "AVISO", Str, ICONE_AVISO);
```

---
