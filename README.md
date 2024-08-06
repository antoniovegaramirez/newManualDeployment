## Running React on Repl.it

[React](https://reactjs.org/) is a popular JavaScript library for building user interfaces.

[Vite](https://vitejs.dev/) is a blazing fast frontend build tool that includes features like Hot Module Reloading (HMR), optimized builds, and TypeScript support out of the box.

Using the two in conjunction is one of the fastest ways to build a web app.

### Getting Started
- Hit run
- Edit [App.jsx](#src/App.jsx) and watch it live update!

By default, Replit runs the `dev` script, but you can configure it by changing the `run` field in the [configuration file](#.replit). Here are the vite docs for [serving production websites](https://vitejs.dev/guide/build.html)

### Typescript

Just rename any file from `.jsx` to `.tsx`. You can also try our [TypeScript Template](https://replit.com/@replit/React-TypeScript)

<main>
  <h1>
    <center>Definición de componentes</center>
  </h1>
  <h2>Botones</h2>
  <Button classStyle="user-button" classIcon="icon-axa-fu001" />
  <Button classStyle="modify-button-table1" classIcon="icon-axa-fu042" />
  <Button classStyle="donwload-button-table1" classIcon="icon-axa-fu018" />
  <Button classStyle="delete-button-table1" classIcon="icon-axa-fu041" />
  <Button
    text="Consulta"
    classStyle="consultation-button-aside"
    classIcon="icon-axa-fu037"
  />
  <Button
    text={"Cerrar sesión"}
    classStyle="close-button-aside"
    classIcon="icon-axa-fu017"
  />
  <Button
    text="Dashboard"
    classStyle="consultation-button-aside"
    classIcon="icon-axa-fu032"
  />
  <Button classStyle="action-button-accordion" classIcon="icon-axa-fu015" />
  <Button classStyle="action-button-accordion" classIcon="icon-axa-fu016" />

  <Button
    text="Guardar"
    classStyle="save-button-accordion"
    classIcon="icon-axa-fu049"
  />

  <Button
    text="Buscar"
    classStyle="search-button-fiters"
    classIcon="icon-axa-fu037"
  />
  <h2>Dropdowns</h2>
  <Dropdown textSelection="opción" /> 
  <InputDate TextInputDate="Fecha"/>
  <InputTime TextInputDate="Hora"/>
  <h2>Input Text</h2>
  <TextField textField="hola"/>
  <TextArea textArea="hola"/>
  <h2>Check Box</h2>
  <CheckBox TextCheckBox="hola"/>
  <h2>Accordions</h2>
  <AccordionsChangeInformation Titulo="1. Información de cambio"/>
  <AccordionAceptSignature Titulo="2. Firmas de aceptación"/>
  <AccordionTrainingFormat Titulo="3. Formato de aceptación"/>
  <AccordionGeneralContactInfo Titulo="4.1. Información general de contacto"/>
  <AccordionPrerequisites Titulo="4.2. Prerequisitos"/>
  <AccordionPrerequisites Titulo="4.3. Plan de implementación"/>
  <AccordionPostImplatationPrerequisite Titulo="4.4. Prerequisittos de Postimplantación"/>
  <AccordionDetailsFuncionalUsers Titulo="4.5. Detalles de usuarios funcionales"/>
  <AccordionBlueprint Titulo="4.7. Blueprint"/>
  <Table/>

  <h2>Vistas rol lider</h2>

  <DashboardLeader/>
  <QueryLeader/>

  <h2>Vistas rol Colaborador</h2>
  <PrincipalCollaboler/>
  <NewDeploymentManual/>
  <Card tittle="hola"/>
</main>