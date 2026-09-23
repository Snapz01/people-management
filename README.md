# People Management

En webbapplikation för personadministration byggd med **ASP.NET Core MVC**[cite: 7]. Projektet demonstrerar ren arkitektur med separation of concerns genom användning av Service- och Repository-mönster samt in-memory-datalagring[cite: 7].

## Funktioner

- **Personhantering:** Skapa, visa detaljer, redigera och ta bort personer via MVC-flöden[cite: 7].
- **Sök- och filtreringsfunktioner:** Möjlighet att lista och filtrera registrerade personer[cite: 7].
- **Modulär arkitektur:** Tydlig ansvarsfördelning med interfaces (`IPeopleService`, `IPeopleRepo`) och dependency injection i ASP.NET Core[cite: 7].
- **Validering:** Formulärvalidering på både klient- och servernivå med ViewModels, Data Annotations och jQuery Unobtrusive Validation[cite: 7].
- **In-Memory-lagring:** Snabb datalagring utan extern databasberoende via `InMemoryPeopleRepo`[cite: 7].

## Projektstruktur

- `Controllers/`: Hanterar HTTP-anrop och vyer (`PeopleController`, `HomeController`)[cite: 7].
- `Interface/`: Abstraktioner för affärslogik och datalager (`IPeopleService`, `IPeopleRepo`)[cite: 7].
- `Services/`: Affärslogik och bearbetning av data (`PeopleService`)[cite: 7].
- `Repositories/`: Datalagringsimplementering (`InMemoryPeopleRepo`)[cite: 7].
- `Models/`: Domänmodeller (`Person`) samt ViewModels för dataöverföring och validering[cite: 7].
- `Views/`: Razor-vyer och partials (`_PersonPartial`) för gränssnittet[cite: 7].

## Teknikstack

- **Backend:** C#, .NET / ASP.NET Core MVC[cite: 7]
- **Mönster & Principer:** Repository Pattern, Service Layer, Dependency Injection, ViewModels[cite: 7]
- **Frontend:** Razor Views, HTML5, CSS3, Bootstrap, jQuery[cite: 7]
