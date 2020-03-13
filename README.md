# Import-csv-File
Import csv File asp.net framework dat base sql server

/////////////////////////////:
script SQL:
CREATE TABLE [dbo].[identi] (
    [Id]       INT            IDENTITY (1, 1) NOT NULL,
    [Name]     NVARCHAR (500) NULL,
    [LastName] NVARCHAR (500) NULL,
    CONSTRAINT [PK_identi] PRIMARY KEY CLUSTERED ([Id] ASC)
);
