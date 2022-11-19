Título: Introdução ao desenvolvimento de plugins para Moodle

Descrição: O moodle é o Sistema de Gestão da Aprendizagem de código aberto mais usado em instituições de ensino de diferentes níveis devido em grande parte a sua capacidade adaptativa através do sistema de plugins. Este curso de Introdução ao desenvolvimento de plugins para Moodle abordará os passos iniciais para construção de um plugin, como chamada de funções, integração com arquitetura do moodle e melhores práticas de desenvolvimento.

Requisito: Conhecimentos básicos PHP, SQL e administração moodle.

Público: Interessados em atuar como desenvolvedores Moodle

Carga horária: 15h

Horário: Segunda, Terça, Quarta, Quinta e Sexta das 19:00 às 22:00;

Período Inicial: ??/01/2023

Período Final: ??/01/2023

Professor: Leônidas de Oliveira Brandao, Thiago Gomes Veríssimo

Bibliografia: 

- Moodle 3.x Developer's Guide, Ian Wild 
- Introduction to Moodle 3.9+ Plugin Development, Benjamin Charles Ellis 


- React: Cousera - Full-Stack Web Development with React
- NodeJs: Cousera - Full-Stack Web Development with React
- Typescript
- Arango DB

Sequência de cursos do https://moodle.academy:

- [ ] Moodle Administration Settings
- [ ] Course Creation Basics
- [ ] Manage Your Users
- [ ] Extend Your Moodle Site
- [ ] Moodle 4.0 for Admins
- [ ] A Window into Workplace

- [ ] Set up your Moodle Development Environment
- [ ] Web Output Essentials
- [ ] Moodle’s Modular Architecture and APIs
- [ ] Moodle Access and Security Essentials
- [ ] Accessible Development Practices
- [ ] Unit Testing in Moodle
- [ ] Update Plugins to Moodle 4.0
- [ ] MoodleNet for Developers

- [ ] Introduction to Moodle
- [ ] Start Teaching with Moodle
- [ ] Moodle Course Content
- [ ] Moodle Course Activities
- [ ] Introduction to Instructional Design
- [ ] Introduction to ABC Learning Design
- [ ] Enhance your Professional Practice
- [ ] Moodle Course Management
- [ ] Accessible Teaching Basics
- [ ] Extend your Moodle Teaching Skills
- [ ] Include Your Learners
- [ ] Engage Your Learners
- [ ] Assess Your Learners
- [ ] Support Your Learners
- [ ] Foster Digital Citizenship
- [ ] Creating Quality Quiz Questions
- [ ] Deliver Effective Virtual Classrooms Using BigBlueButton
- [ ] Moodle 4.0 for Educators
- [ ] Facilitating Moodle Forums

Cursos antigos:

- https://learn.moodle.org/course/view.php?id=26428



Ideias de projetos:

- http://200.144.254.107/git/thiagogomesverissimo/gradeimporter
- Transformar um jogo/atividade educativa em tarefa do moodle (com ou sem h5p?)


externalsync

    tabela sistema local:
        
      externalsync_users:
       
        user_moodle_id (se vazio implica erro)
        user_local_id
        exported_date (do sistema local para o moodle)
        resposta: resposta do moodle
        
      externalsync_courses
      
        course_moodle_id (se vazio implica erro)
        course_local_id
        exported_date (do sistema local para o moodle)
        resposta: resposta do moodle
       
        
      externalsync_emails:

        user_moodle_id
        email
        data_inativacao
        
        
     Emitir relatório;boletim com status da importação