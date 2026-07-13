# RepoNuevo

ESQUEMA DE FIRMAS CONSULTAS A LA BASE DE DATOS

Select *  from qasib.esquemas_firmas
Where ent_id = '39956151'; /*39132146 NOVA         39344147 Velizi       39956151 antisocial*/

Select * from qasib.tope_cta
Where esq_firm_id = '417147';

Select * from qasib.tope_tef
Where tope_id = '8609639';

Select *
from qasib.cotizacion;

/*Velizi*/
Select *
from qasib.esquemas_listas
Where esq_firm_id in ('403119',
'416672',
'416585',
'416559');

/*Nova*/
Select *
from qasib.esquemas_listas
Where esq_firm_id in ( '413241',
'400750',
'401219',
'405882');

Select *
from qasib.entidades;
/*39956151 antisocial*/
