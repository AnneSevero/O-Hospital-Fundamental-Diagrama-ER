CREATE DATABASE  IF NOT EXISTS `hospital` /*!40100 DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_0900_ai_ci */ /*!80016 DEFAULT ENCRYPTION='N' */;
USE `hospital`;
-- MySQL dump 10.13  Distrib 8.0.27, for Win64 (x86_64)
--
-- Host: localhost    Database: hospital
-- ------------------------------------------------------
-- Server version	8.0.27

/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!50503 SET NAMES utf8 */;
/*!40103 SET @OLD_TIME_ZONE=@@TIME_ZONE */;
/*!40103 SET TIME_ZONE='+00:00' */;
/*!40014 SET @OLD_UNIQUE_CHECKS=@@UNIQUE_CHECKS, UNIQUE_CHECKS=0 */;
/*!40014 SET @OLD_FOREIGN_KEY_CHECKS=@@FOREIGN_KEY_CHECKS, FOREIGN_KEY_CHECKS=0 */;
/*!40101 SET @OLD_SQL_MODE=@@SQL_MODE, SQL_MODE='NO_AUTO_VALUE_ON_ZERO' */;
/*!40111 SET @OLD_SQL_NOTES=@@SQL_NOTES, SQL_NOTES=0 */;

--
-- Table structure for table `consultas`
--

DROP TABLE IF EXISTS `consultas`;
/*!40101 SET @saved_cs_client     = @@character_set_client */;
/*!50503 SET character_set_client = utf8mb4 */;
CREATE TABLE `consultas` (
  `id_consulta` int NOT NULL,
  `id_medico` int DEFAULT NULL,
  `nome_paciente` varchar(100) DEFAULT NULL,
  `convenio` varchar(100) DEFAULT NULL,
  `data_da_consulta` date DEFAULT NULL,
  `medicamento` int DEFAULT NULL,
  PRIMARY KEY (`id_consulta`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;
/*!40101 SET character_set_client = @saved_cs_client */;

--
-- Dumping data for table `consultas`
--

LOCK TABLES `consultas` WRITE;
/*!40000 ALTER TABLE `consultas` DISABLE KEYS */;
INSERT INTO `consultas` VALUES (1,1,'José Silva','Convênio A','2015-03-10',1),(2,15,'Maria Oliveira','Convênio B','2016-06-22',20),(3,10,'Ana Santos','Convênio C','2017-01-15',3),(4,7,'Carlos Pereira','Convênio A','2018-04-05',14),(5,5,'Patrícia Rocha','Convênio B','2019-09-28',55),(6,6,'Felipe Almeida','Convênio C','2020-12-10',67),(7,12,'Laura Costa','Convênio A','2021-05-18',37),(8,7,'Rafael Nunes','Convênio B','2022-01-02',18),(9,9,'Camila Mendes','Convênio C','2016-07-14',9),(10,10,'Bruno Rodrigues','Convênio A','2017-11-30',11),(11,15,'Bruno Rodrigues','Convênio A','2017-12-10',11),(12,2,'Thiago Alvez','Convênio A','2021-09-30',10),(13,8,'Cezar Menoti','Convênio A','2020-01-20',10),(14,11,'Patrícia Rocha','Convênio B','2021-04-06',10),(15,14,'Bruno Rodrigues','Convênio A','2019-11-30',17),(16,3,'Laura Costa','Convênio A','2016-12-31',9),(17,5,'Emerson Madruga','Convênio A','2019-07-13',18),(18,4,'Emerson Madruga','Convênio A','2019-07-23',20),(19,13,'Emerson Madruga','Convênio A','2019-08-03',13),(20,14,'Gilmar Toledo','Convênio A','2018-09-30',10);
/*!40000 ALTER TABLE `consultas` ENABLE KEYS */;
UNLOCK TABLES;

--
-- Table structure for table `enfermeiros`
--

DROP TABLE IF EXISTS `enfermeiros`;
/*!40101 SET @saved_cs_client     = @@character_set_client */;
/*!50503 SET character_set_client = utf8mb4 */;
CREATE TABLE `enfermeiros` (
  `id_enfermeiro` int NOT NULL,
  `nome_enfermeiro` varchar(100) DEFAULT NULL,
  PRIMARY KEY (`id_enfermeiro`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;
/*!40101 SET character_set_client = @saved_cs_client */;

--
-- Dumping data for table `enfermeiros`
--

LOCK TABLES `enfermeiros` WRITE;
/*!40000 ALTER TABLE `enfermeiros` DISABLE KEYS */;
INSERT INTO `enfermeiros` VALUES (1,'Eliane Martins'),(2,'Gisely Alvez'),(3,'Maria Clara'),(4,'Jhonatan Souza'),(5,'Stefany Lais'),(6,'Melissa Maia'),(7,'Beatriz Cunha'),(8,'Gabriel Ferrari'),(9,'Douglas Ferreira'),(10,'Giusep Lamborguini'),(11,'Mercedes da Silva'),(12,'Monalisa Albertina'),(13,'Willians Smith');
/*!40000 ALTER TABLE `enfermeiros` ENABLE KEYS */;
UNLOCK TABLES;

--
-- Table structure for table `internacoes`
--

DROP TABLE IF EXISTS `internacoes`;
/*!40101 SET @saved_cs_client     = @@character_set_client */;
/*!50503 SET character_set_client = utf8mb4 */;
CREATE TABLE `internacoes` (
  `id_internacao` int NOT NULL,
  `nome_paciente` varchar(100) DEFAULT NULL,
  `data_de_internacao` date DEFAULT NULL,
  `data_de_alta` date DEFAULT NULL,
  `previsao_de_alta` date DEFAULT NULL,
  `quarto` varchar(100) DEFAULT NULL,
  `enfermeiro` varchar(100) DEFAULT NULL,
  PRIMARY KEY (`id_internacao`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;
/*!40101 SET character_set_client = @saved_cs_client */;

--
-- Dumping data for table `internacoes`
--

LOCK TABLES `internacoes` WRITE;
/*!40000 ALTER TABLE `internacoes` DISABLE KEYS */;
INSERT INTO `internacoes` VALUES (1,'José Silva','2015-06-10','2015-06-15','2015-06-14','Apartamento','Eliane Martins'),(2,'Maria Oliveira','2016-08-25','2016-09-01','2016-08-28','Quarto Duplo','Giusep Lamborguini'),(3,'Ana Santos','2017-03-18','2017-03-25','2017-03-22','Enfermaria','Douglas Ferreira'),(4,'Carlos Pereira','2018-06-05','2018-06-12','2018-06-10','Apartamento','Gisely Alvez'),(5,'Patrícia Rocha','2019-10-22','2019-11-01','2019-10-28','Quarto Duplo','Mercedes da Silva'),(6,'Felipe Almeida','2020-01-15','2020-01-25','2020-01-22','Enfermaria','Beatriz Cunha'),(7,'Laura Costa','2021-07-08','2021-07-18','2021-07-15','Apartamento','Melissa Maia'),(8,'Fabio Menoti','2020-01-08','2020-01-20','2020-01-20','Quarto Duplo','Willians Smith'),(9,'Emerson Madruga','2019-07-18','2019-07-30','2019-07-27','Apartamento','Monalisa Albertina'),(10,'José Silva','2019-06-10','2019-06-15','2019-06-14','Apartamento','Eliane Martins'),(11,'Emerson Madruga','2018-05-11','2018-05-15','2019-05-14','Apartamento','Willians Smith');
/*!40000 ALTER TABLE `internacoes` ENABLE KEYS */;
UNLOCK TABLES;

--
-- Table structure for table `medicos`
--

DROP TABLE IF EXISTS `medicos`;
/*!40101 SET @saved_cs_client     = @@character_set_client */;
/*!50503 SET character_set_client = utf8mb4 */;
CREATE TABLE `medicos` (
  `id_medicos` int NOT NULL,
  `nome_medico` varchar(100) DEFAULT NULL,
  `especialidade` varchar(100) DEFAULT NULL,
  PRIMARY KEY (`id_medicos`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;
/*!40101 SET character_set_client = @saved_cs_client */;

--
-- Dumping data for table `medicos`
--

LOCK TABLES `medicos` WRITE;
/*!40000 ALTER TABLE `medicos` DISABLE KEYS */;
INSERT INTO `medicos` VALUES (1,'Dr. João Silva','Clinica Geral'),(2,'Dra. Maria Santos','Pediatria'),(3,'Dr. Carlos Oliveira','Gastroenterologia'),(4,'Dra. Ana Pereira','Dermatologia'),(5,'Dr. Pedro Rocha','Cardiologia'),(6,'Dra. Laura Mendes','Gastrenterologia '),(7,'Dr. Rafael Almeida','Pediatria'),(8,'Dra. Beatriz Nunes','Clinica Geral'),(9,'Dr. Bruno Costa','Clinica Geral'),(10,'Dra. Camila Rodrigues','Clinica Geral'),(11,'Dra. Roberta Magalhaes','Pediatria'),(12,'Dra. Bruna Alves','Pediatria'),(13,'Dra. Gbriela Porttinari','Clinica Geral'),(14,'Dr. Josefino de Oliveira','Gastrenterologia'),(15,'Dr. Claudio Gomes','Gastrenterologia');
/*!40000 ALTER TABLE `medicos` ENABLE KEYS */;
UNLOCK TABLES;

--
-- Table structure for table `pacientes`
--

DROP TABLE IF EXISTS `pacientes`;
/*!40101 SET @saved_cs_client     = @@character_set_client */;
/*!50503 SET character_set_client = utf8mb4 */;
CREATE TABLE `pacientes` (
  `id_paciente` int NOT NULL,
  `nome_paciente` varchar(100) DEFAULT NULL,
  `data_de_nascimento` date DEFAULT NULL,
  `convenio` varchar(100) DEFAULT NULL,
  PRIMARY KEY (`id_paciente`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;
/*!40101 SET character_set_client = @saved_cs_client */;

--
-- Dumping data for table `pacientes`
--

LOCK TABLES `pacientes` WRITE;
/*!40000 ALTER TABLE `pacientes` DISABLE KEYS */;
INSERT INTO `pacientes` VALUES (1,'José Silva','1990-05-15','Convênio A'),(2,'Maria Oliveira','1985-08-22','Convênio B'),(3,'Ana Santos','2000-02-10','Convênio C'),(4,'Carlos Pereira','1975-11-30','Convênio A'),(5,'Patrícia Rocha','1995-04-18','Convênio B'),(6,'Felipe Almeida','1980-07-25','Convênio C'),(7,'Laura Costa','1998-09-12','Convênio A'),(8,'Rafael Nunes','1992-12-05','Convênio B'),(9,'Camila Mendes','1987-03-08','Convênio C'),(10,'Bruno Rodrigues','1978-06-20','Convênio A'),(11,'Gilmar Toledo','1970-12-29','Convênio A'),(12,'Thiago Alvez','1978-03-25','Convênio A'),(13,'Cezar Menoti','1988-06-08','Convênio A'),(14,'Fabio Menoti','1988-06-08','Convênio A'),(15,'Emerson Madruga','1999-09-19','Convênio A');
/*!40000 ALTER TABLE `pacientes` ENABLE KEYS */;
UNLOCK TABLES;

--
-- Table structure for table `quartos`
--

DROP TABLE IF EXISTS `quartos`;
/*!40101 SET @saved_cs_client     = @@character_set_client */;
/*!50503 SET character_set_client = utf8mb4 */;
CREATE TABLE `quartos` (
  `id_quarto` int NOT NULL,
  `tipo_de_quarto` varchar(100) DEFAULT NULL,
  PRIMARY KEY (`id_quarto`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;
/*!40101 SET character_set_client = @saved_cs_client */;

--
-- Dumping data for table `quartos`
--

LOCK TABLES `quartos` WRITE;
/*!40000 ALTER TABLE `quartos` DISABLE KEYS */;
INSERT INTO `quartos` VALUES (1,'Apartamento'),(2,'Quarto Duplo'),(3,'Enfermaria');
/*!40000 ALTER TABLE `quartos` ENABLE KEYS */;
UNLOCK TABLES;
/*!40103 SET TIME_ZONE=@OLD_TIME_ZONE */;

/*!40101 SET SQL_MODE=@OLD_SQL_MODE */;
/*!40014 SET FOREIGN_KEY_CHECKS=@OLD_FOREIGN_KEY_CHECKS */;
/*!40014 SET UNIQUE_CHECKS=@OLD_UNIQUE_CHECKS */;
/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
/*!40111 SET SQL_NOTES=@OLD_SQL_NOTES */;
