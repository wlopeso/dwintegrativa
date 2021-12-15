# integrativa 

## TODO:
TODO: 
  Si los datos ingresados no existen debe otorgar oportunidad de registrarse ingresando todos los
  datos de la tabla DatosPersonales. Para lo cual:
    i. Agregar a tabla el campo origen, el cual dependerá de la tabla orígenes.
    ii. El usuario debe ingresar sus datos personales identificados en tabla.
    iii. Según los datos ingresados se entregará automáticamente como nombre de usuario Los
      3 primeros dígitos del nombre más guión Bajo más el apellido paterno más la inicial del
      apellido materno (ejemplo para Luis Yanez Carreno LUI_YanezC).
    iv. Se entregará automáticamente como clave la inicial del nombre más la inicial del
    apellido paterno más el rut (LY11111111-1).
    v. Se asignará al nuevo usuario el nivel de cliente.
# TODO: cambiar el titulo del campo identificacion por rut en el formulario de creacion de usuario

# USUARIOS 
will@will.com
123456

Jua_Silva
JS1-1

# TODO:
  agregar mensaje confirmacion de registro USUARIO LOGIN (ok)
  CAMBIAR EL TIPO DE MONEDA (ok)
  CAMBIAR PALABRA EMAIL POR USUARIO Y LA PALABRA IDENTIFICACION POR RUT 
  AGREGAR VALIDADOR DEL RUT


#
Seb_Zuniga
SZ16519854-9

##
INSERT INTO `dw-integrativa`.persona
(idpersona, identificacion, nombres, apellidos, telefono, email_user, password, nit, nombrefiscal, direccionfiscal, token, rolid, datecreated, status)
VALUES(1, '14153499-8', 'will', 'lopez', 123456, 'will@will.com', '8d969eef6ecad3c29a3a629280e686cf0c3f5d5a86aff3ca12020c923adc6c92', 'CF', 'will', 'Ciudad', NULL, 1, '2021-08-20 01:34:15', 1);
INSERT INTO `dw-integrativa`.persona
(idpersona, identificacion, nombres, apellidos, telefono, email_user, password, nit, nombrefiscal, direccionfiscal, token, rolid, datecreated, status)
VALUES(2, '24091990', 'PruebaSup', 'PruebaSup', 456878977, 'pruebasup@pruebasup.com', '8d969eef6ecad3c29a3a629280e686cf0c3f5d5a86aff3ca12020c923adc6c92', NULL, NULL, NULL, NULL, 2, '2021-08-20 02:58:47', 1);
INSERT INTO `dw-integrativa`.persona
(idpersona, identificacion, nombres, apellidos, telefono, email_user, password, nit, nombrefiscal, direccionfiscal, token, rolid, datecreated, status)
VALUES(3, '84654864', 'PruebaCli', 'PruebaCli', 4687987, 'pruebacli@pruebacli.com', '8d969eef6ecad3c29a3a629280e686cf0c3f5d5a86aff3ca12020c923adc6c92', '468798', 'Ricardo HP', 'Ciudad de Guatemala', NULL, 3, '2021-08-20 03:41:28', 1);
INSERT INTO `dw-integrativa`.persona
(idpersona, identificacion, nombres, apellidos, telefono, email_user, password, nit, nombrefiscal, direccionfiscal, token, rolid, datecreated, status)
VALUES(4, '798465877', 'PruebaVen', 'PruebaVen', 468498, 'pruebaven@pruebaven.com', '8d969eef6ecad3c29a3a629280e686cf0c3f5d5a86aff3ca12020c923adc6c92', NULL, NULL, NULL, NULL, 4, '2021-08-21 18:07:00', 1);
INSERT INTO `dw-integrativa`.persona
(idpersona, identificacion, nombres, apellidos, telefono, email_user, password, nit, nombrefiscal, direccionfiscal, token, rolid, datecreated, status)
VALUES(5, 'qweqwe', 'Qweqwe', 'Qweqwe', 0, 'Qwe_Qweqwe', '2846254e56b9fbbe62322a80fd32a6548d66aa15791c78b5590fafb407ab3ca0', NULL, NULL, NULL, NULL, 3, '2021-12-13 23:05:24', 1);
INSERT INTO `dw-integrativa`.persona
(idpersona, identificacion, nombres, apellidos, telefono, email_user, password, nit, nombrefiscal, direccionfiscal, token, rolid, datecreated, status)
VALUES(6, '1-1', 'Juanito', 'Silva', 123456, 'Jua_Silva', '26e2a28d769a6066770e3d70524df4602cd6023a3a25e04067b0eb97668de47d', NULL, NULL, NULL, NULL, 3, '2021-12-13 23:07:37', 1);
INSERT INTO `dw-integrativa`.persona
(idpersona, identificacion, nombres, apellidos, telefono, email_user, password, nit, nombrefiscal, direccionfiscal, token, rolid, datecreated, status)
VALUES(7, '123', '123', '123', 123, '123_123', 'ce7e5e6863602b6e16fc8615bc27b54a323879174fe89e491f86fef49b2916d1', NULL, NULL, NULL, NULL, 3, '2021-12-14 22:19:40', 1);
INSERT INTO `dw-integrativa`.persona
(idpersona, identificacion, nombres, apellidos, telefono, email_user, password, nit, nombrefiscal, direccionfiscal, token, rolid, datecreated, status)
VALUES(8, '111', '111', '111', 111, '111_111', 'd17f25ecfbcc7857f7bebea469308be0b2580943e96d13a3ad98a13675c4bfc2', NULL, NULL, NULL, NULL, 3, '2021-12-14 22:21:34', 1);
INSERT INTO `dw-integrativa`.persona
(idpersona, identificacion, nombres, apellidos, telefono, email_user, password, nit, nombrefiscal, direccionfiscal, token, rolid, datecreated, status)
VALUES(9, '33', '333', '3333', 333, '333_3333', '318aee3fed8c9d040d35a7fc1fa776fb31303833aa2de885354ddf3d44d8fb69', NULL, NULL, NULL, NULL, 3, '2021-12-14 22:22:59', 1);
INSERT INTO `dw-integrativa`.persona
(idpersona, identificacion, nombres, apellidos, telefono, email_user, password, nit, nombrefiscal, direccionfiscal, token, rolid, datecreated, status)
VALUES(10, '444', '4444', '444', 444, '444_444', 'e11d8cb94b54e0a2fd0e780f93dd51837fd39bf0c9b86f21e760d02a8550ddf7', NULL, NULL, NULL, NULL, 3, '2021-12-14 22:26:28', 1);
INSERT INTO `dw-integrativa`.persona
(idpersona, identificacion, nombres, apellidos, telefono, email_user, password, nit, nombrefiscal, direccionfiscal, token, rolid, datecreated, status)
VALUES(11, '5555', '55555', '5555', 555, '555_5555', 'af41e68e1309fa29a5044cbdc36b90a3821d8807e68c7675a6c495112bc8a55f', NULL, NULL, NULL, NULL, 3, '2021-12-14 22:27:43', 1);
INSERT INTO `dw-integrativa`.persona
(idpersona, identificacion, nombres, apellidos, telefono, email_user, password, nit, nombrefiscal, direccionfiscal, token, rolid, datecreated, status)
VALUES(12, '77777', '77777', '77777', 77777, '777_77777', '8c1cdb9cb4dbac6dbb6ebd118ec8f9523d22e4e4cb8cc9df5f7e1e499bba3c10', NULL, NULL, NULL, NULL, 3, '2021-12-14 22:28:51', 1);
INSERT INTO `dw-integrativa`.persona
(idpersona, identificacion, nombres, apellidos, telefono, email_user, password, nit, nombrefiscal, direccionfiscal, token, rolid, datecreated, status)
VALUES(13, '99999', '9999', 'Jujujuju', 9999, '999_Jujujuju', 'e01ca1a789a80001c4d6806392ebf31056480685d7b219e2e77413522a929292', NULL, NULL, NULL, NULL, 3, '2021-12-14 22:29:59', 1);
INSERT INTO `dw-integrativa`.persona
(idpersona, identificacion, nombres, apellidos, telefono, email_user, password, nit, nombrefiscal, direccionfiscal, token, rolid, datecreated, status)
VALUES(14, '16519854-9', 'Sebastian', 'Zuniga', 1234567, 'Seb_Zuniga', '6b5cfb6cc40c50a9d36271a2e4ebd9b21b59e1012033020fa6f8241b1c6ec083', NULL, NULL, NULL, NULL, 1, '2021-12-14 23:31:17', 1);