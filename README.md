# TFG DAW
 
# Diagrama de Flujo del Proyecto

```xml
<mxfile host="app.diagrams.net">
  <diagram name="Diagrama de Flujo del Proyecto">
    <mxGraphModel dx="1008" dy="605" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="2" value="Inicio" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="340" y="50" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="3" value="Autenticación del Usuario" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="320" y="150" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="4" value="Usuario Inicia Sesión" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="100" y="250" width="140" height="60" as="geometry" />
        </mxCell>
        <mxCell id="5" value="Usuario No Autenticado" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="460" y="250" width="160" height="60" as="geometry" />
        </mxCell>
        <mxCell id="6" value="Fin" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="500" y="360" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="7" value="Página de Inicio" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="100" y="350" width="140" height="60" as="geometry" />
        </mxCell>
        <mxCell id="8" value="Ver Lista de Cursos" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="100" y="450" width="140" height="60" as="geometry" />
        </mxCell>
        <mxCell id="9" value="Seleccionar Curso" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="100" y="550" width="140" height="60" as="geometry" />
        </mxCell>
        <mxCell id="10" value="Ver Detalles del Curso" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="100" y="650" width="160" height="60" as="geometry" />
        </mxCell>
        <mxCell id="11" value="Ver Ejercicio Actual" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="100" y="750" width="160" height="60" as="geometry" />
        </mxCell>
        <mxCell id="12" value="Introducir Código" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="100" y="850" width="140" height="60" as="geometry" />
        </mxCell>
        <mxCell id="13" value="Enviar Código a API de Gemini AI" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="100" y="950" width="180" height="60" as="geometry" />
        </mxCell>
        <mxCell id="14" value="Recibir Respuesta y Nota" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="100" y="1050" width="160" height="60" as="geometry" />
        </mxCell>
        <mxCell id="15" value="Guardar en Firebase Firestore" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="100" y="1150" width="180" height="60" as="geometry" />
        </mxCell>
        <mxCell id="16" value="Ejercicio Siguiente Disponible" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="320" y="1250" width="160" height="60" as="geometry" />
        </mxCell>
        <mxCell id="17" value="Navegar al Siguiente Ejercicio" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="100" y="1350" width="200" height="60" as="geometry" />
        </mxCell>
        <mxCell id="18" value="Ejercicio Completo" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="460" y="1350" width="140" height="60" as="geometry" />
        </mxCell>
        <mxCell id="19" value="Fin" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="500" y="1460" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="20" edge="1" parent="1" source="2" target="3">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="21" edge="1" parent="1" source="3" target="4">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="22" edge="1" parent="1" source="3" target="5">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="23" edge="1" parent="1" source="5" target="6">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="24" edge="1" parent="1" source="4" target="7">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="25" edge="1" parent="1" source="7" target="8">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="26" edge="1" parent="1" source="8" target="9">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="27" edge="1" parent="1" source="9" target="10">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="28" edge="1" parent="1" source="10" target="11">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="29" edge="1" parent="1" source="11" target="12">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="30" edge="1" parent="1" source="12" target="13">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="31" edge="1" parent="1" source="13" target="14">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="32" edge="1" parent="1" source="14" target="15">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="33" edge="1" parent="1" source="15" target="16">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="34" edge="1" parent="1" source="16" target="17">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="35" edge="1" parent="1" source="16" target="18">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="36" edge="1" parent="1" source="18" target="19">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
```
