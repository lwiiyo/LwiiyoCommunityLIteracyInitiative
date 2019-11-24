USE [Training]
GO

/****** Object:  Table [dbo].[Person]    Script Date: 11/23/2019 10:49:21 ******/
SET ANSI_NULLS ON
GO

SET QUOTED_IDENTIFIER ON
GO

CREATE TABLE [dbo].[Person](
	[Name] [nvarchar](max) NULL,
	[Age] [int] NULL,
	[City] [nchar](10) NULL
) ON [PRIMARY]

GO
