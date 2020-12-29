# Helloworld
SAP15
class AuditConf(object):
	# pylint: disable=too-many-instance-attributes
	def __init__(self, host=None, port=22):
		# type: (Optional[str], int) -> None
		self.host = host
		self.port = port
		self.ssh1 = True
		self.ssh2 = True
		self.batch = False
		self.colors = True
		self.verbose = False
		self.minlevel = 'info'
		self.ipvo = ()  # type: Sequence[int]
		self.ipv4 = False
		self.ipv6 = False
