SITE DO GUIGOCDP - COMO COLOCAR NO AR

1) Baixe este projeto e extraia.
2) Suba para um repositório no GitHub.
3) Entre em vercel.com.
4) Clique em Add New > Project.
5) Importe o repositório.
6) Clique em Deploy.

COMO ADICIONAR NOVOS BEATS

1) Coloque o novo MP3 na pasta public/audio.
2) Abra o arquivo app/page.tsx.
3) No topo, dentro da constante beats, adicione um novo bloco assim:

  {
    title: "Nome do Beat",
    price: "R$ 30,00",
    duration: "2:10",
    previewUrl: "/audio/nome-do-arquivo.mp3",
  },

4) Salve.
5) Faça novo deploy na Vercel.

COMO TROCAR PREÇO

No arquivo app/page.tsx, troque "R$ 30,00" pelo novo valor.

COMO TROCAR WHATSAPP, INSTAGRAM E PIX

No arquivo app/page.tsx, edite a constante contactLinks.
