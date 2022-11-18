# AngularEscola

https://jacksongomesbr.gitbooks.io/desenvolvimento-web-front-end-com-angular/content/conceitos-iniciais/editando-dados-de-uma-disciplina.html

<ul>
  <li *ngFor="let disciplina of disciplinas" (click)="selecionar(disciplina)">
      <p [class.selecionado]="selecionado == disciplina">{{disciplina.nome}}</p>
      <p *ngIf="selecionado == disciplina">{{disciplina.descricao}}</p>
  </li>
</ul>