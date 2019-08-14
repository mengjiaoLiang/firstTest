# firstTest
my first repository
{dede:channelartlist typeid='1,7,2,3,4,5,6' }
	<!-- 上级栏目链接 --> 						<!-- 调取上级栏目名 -->
	<a href="{dede:field name='typeurl'/}">{dede:field name='typename'/}</a>
	<ul>
		<!-- 调取二级栏目 -->
		{dede:channel type='son'}
		<li><a href="[field:typelink/]">[field:typename/]</a></li>
		{/dede:channel}
	</ul>
{/dede:channelartlist}
