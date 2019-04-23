worker: python yaboi.py
import discord
from discord.ext import commands
from discord.ext.commands import bot
import asyncio

my_token = 'token'

client = commands.Bot(command_prefix = '?')

@client.event
async def on_ready():
    print('The bot is online and is connected to discord')
        
@client.command(pass_context=True)
async def ping(ctx):
    await ctx.send('dont ping me ill eat your kids!')
    
   
@client.command()
async def repeat(ctx, times, *, text):
    """Repeats a message multiple times."""
    for i in range(times):
        await ctx.send(content)

client.run('NTY5MDAzMDE2NTMyMDAwNzY5.XLqTtA.zbYzfW8HC5pFb8rMu0-1aivcGUI')
