<h1>Mostrar Tabuada</h1>
<p>Script para melhorias</p>
<pre>
	<?php $numero = array(1,2,3,4,5,6,7,8,9);?>
	<?php $total = count($numero);?>
	<table border="1" width="500">
		<?php foreach($numero as $numero):?>
			<tr>
				<?php for($i = 1;$i<=$total;$i++ ):?>
					<td><?php echo $i * $numero;?></td>
				<?php endfor;?>
			</tr>
		<?php endforeach;?>
	</table>
</pre>