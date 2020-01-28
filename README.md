import discord
from discord.ext import commands

bot = commands.Bot(command_prefix='', description="Bot conteston")

@bot.command()
async def ping(ctx):
    await ctx.send('pong')

@bot.command()
async def XD(ctx):
    await ctx.send('XDXD')

@bot.command()
async def F(ctx):
    await ctx.send('en el chat chavales')

@bot.command()
async def ola(ctx):
    await ctx.send('PUTO MANCO DE MIERDA ME CAGAS')

@bot.command()
async def musica(ctx):
    await ctx.send('no se hacer eso aún XDDDDDD')

@bot.command()
async def joto(ctx):
    await ctx.send('A que bn puto niño rata de mierda lo deje callado oke mijo')

@bot.command()
async def owo(ctx):
    await ctx.send('OWO')

@bot.command()
async def Kerene(ctx):
    await ctx.send('wele a otaku')

@bot.command()
async def Jahir(ctx):
    await ctx.send('Tambien y esta bien puñetas')

@bot.command()
async def manco(ctx):
    await ctx.send('de mierda')

@bot.command()
async def united(ctx):
    await ctx.send('SUTEIIITSU OFU SUMAAAAAAASHU!!!!!')

@bot.command()
async def ayuda(ctx):
    await ctx.send('Comandos: ping, XD, ola, musica, joto, owo, manco, united y el mismisimo ayuda :B')

# Evento
@bot.event
async def on_ready():
    print("La Unión Soviética, oficialmente llamada Unión de Repúblicas Socialistas Soviéticas ​, siendo Soviet en castellano 'Consejo', fue un Estado federal de repúblicas socialistas que existió entre 1922 y 1991 en Eurasia.​")
    await bot.change_presence(activity=discord.Streaming(name="Geimer pro", url="htpp://www.twitch.com/fernanelcrack"))
bot.run('NjcxNTU1NDMyNDg1MDkzNDM4.Xi-rIw._dFQG40yQEqV4bcXnipmxLtoRuA')
